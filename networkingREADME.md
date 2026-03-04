# NETWORK + Battle Plan 



                                                    at home ready labs, vids, lectures. 


                                                    # Week #

                                                    ## Batttle Plan Tracker 
                                                    <!-- 

                                                    *1. Lectures 

                                                    *2. (a) Videos & their questions

                                                    *3. At Home Graded Labs 

                                                    *4. Learning lab 

                                                    *5. Study Guide Notes 

                                                    *6. Final Exam Review

                                                    *7. Homework Questions -->

                                                    ## Lectures 


                                                    ## Learning labs (Flex)


                                                    ## Video & Their Questions  



                                                    ## At Home Graded Labs



                                                    ## Study Guide Notes 



                                                    ## Final Exam Review



                                                    ## Homework Assingment  
<!--------------------------------------------START!!---------------------------------------------------------->

# Week 1 
<!-- 
?Instructors: 

    Candice Kiser
    919.300.7031
    candice.kiser@mycomputercareer.edu

    Mark Firkus
    919.346.0425
    mark.firkus@mycomputercareer.edu


 -->

## Battle Plan Tracker 
<!-- 

    *1. Lectures 

    *2. (a) Videos & their questions

    *3. At Home Graded Labs 

    *4. Learning lab 

    *5. Study Guide Notes 

    *6. Final Exam Review

    *7. Homework Questions -->


## Lectures 
<!-- 

! Need to get the keys tomorrow during Flex !!!!!!!!!

https://drive.google.com/drive/u/0/folders/1tzds79XCfw60da3yebkmk2DNIMOzeNaP

Protocols & Ports Game: https://wordwall.net/resource/28743938/comptia-protocols-and-ports





?Candice Course info:

    *TIPs 
    
    1. Google Drive has alot of study material! 
    2. Check out the syllabus 
    3. Lecture notes posted after each lesson 

    *Comptia Information 

    -80% score needed to pass
    -See Comptia Networking objectives 
    -quick reference notes 


    *My question
    What are the best course materials out of all of them to study to learn everything well / pass the exam

? Netowrking Notes Starts! -------------------------------------------------------------------------------



?Vocabulary 

*Simple way to remember Client-Server networks 

*Peer to Peer 
    
    Workgroups 
    -Peer to peer setup-no cnetral authority. 
    -Each computer manages it's own users and resources. 
    -Better for smaller networks (=>20 machines)
    -i.e: small home network, where each PC is independent 



*Client-Server 
    
    Active Directory = the tool that manages it
        Domain/Workgroup = the choice you make when setting it up

    *Client Server 
    -A network model where one or more servers provide resources or services
    -Clients (user machines) request & consume those resources 

        i. Server handles
            -file storage 
            -authentication
            -email
            -web hosting 

        ii. Clients connect to server to access those resources 

        iii. This is the foundation of most business networks and what Active Directory runs on top of. 


        *Active Directory (Domain Controller-Based Server) 
        Centralized network managed by a domain controller server which controls 
            -users access (authentication) 
            -network group policies across an entire network (think RBAC) 
            -used in corperate environments 
            NOTE: Active Directory runs on a Client Server Setup 


            * Domain (DomainController ActiveDirectory type)
                -All computers and users are joined to a central domain and managed by the Domain Controller. 
                -Admin: pushes policies, reset passwords, and control permissions from one place    
                - i.e: a company where IT manages everyones login 

       
*Local Area Network 
confined to a single geographical location (building single room/floor)

    Types: 
    
    a. SOHO (Small Office Home Office)
            Soho Routers: 
            -Are WAP, switches, and x ... all in one 
            -apart of the Data Link Layer (see OSI for more info)

    b. Enterprise LAN


    c. Datacenter


*Topologies 
Different physical layouts of how devices are connected in a network.  


    *Point-to-Point:
                 A ——— B
    -Direct connect between 2 devices 


    *Star:
                    A
                    |
                C —— Switch —— B
                    |
                    D
    -all devices connect to a central hub/switch. 
    -if one device fails, the others stay up. 
    -If te central switch fails, everything goes down 

    
    *Mesh:       A ——— B
                |  X  |
                C ——— D
    -every devices connects to multiple other devices. 
    -if one path fails, traffic reroutes.
    -used in data centers/enterprise where uptime is critical 


            *Partial Mesh:
                    A ——— B
                    |     |
                    C ——— D ——— E
                    (E only has one connection, not fully redundant)
            -critical devies get redundancy
            -less important ones only get one 


    *Ring 
                 A
                / \
                E  B
                |  |
                D  C
                \ / 
                    (loop)
    -each devies connects to exactly two other devices, creating a circle 
        -pros: predictable performance, no data collisions 
        -cons: one things breaks in a single ring, ya done! 

    
*OSI Layers 


| # | Layer | Job | Components |

| 8 | "Layer 8" or User error HA! 

| 7 | Application | User-facing protocols | DNS, DHCP | AppData, HTML,DNS

| 6 | Presentation | Formatting, encryption | — | HTML,png,GIF

| 5 | Session | Opens/maintains connections | — | start/stop a session

| 4 | Transport | TCP/UDP, error checking | — | Segments

| 3 | Network | Routing, IP addressing | Routers, ISP, AR | Packets 

| 2 | Data Link | MAC addressing, frames | Ethernet switches, MAC, WAPs | frames/Switches  

| 1 | Physical | Cables, signals, bits | Host interfaces (NICs), physical cables | bits 


    OFNOTE:
    - **DNS & DHCP** — Application layer protocols (support lower layer functions)

    - **ARP** — Operates between Layer 2 and 3 (sometimes called Layer 2.5)

    - **ISP** — Handles routing between networks via IP (Layer 3)

    - **Routers** — Layer 3 devices; WAPs and switches are Layer 2


*Memory trick (top → bottom):
 All People Seem To Need Data Processing  
 7     6      5  4   3    2      1       
  

?Physical Layer 
 
OFNOTE: 
    -T in cable names denotes it's ethernet
    -Cables are twisted to prevent crosstalk & EMI
    -Be able to distinguish between Fiber/Ethernet Cables 


*Ethenet Cables 

    CAT 3, 
        -Ethernet; 10Mbps; 100m (300ft); "10 Base T"  
        -Very Slow
        -Limited Connection Range  

    CAT 5, 
        -Fast Ethernet; 100 Mbps; 100m  
        -when using this both ends would be equal (back in the day)
    
    CAT 5e, 
        -Gigabit Ethernet; 1000 mbps (1 Gbps); 100m  
        -preferred cable for home LAN 
        -everything is made straight through in this cable now 

    CAT 6, 
        -Gigabit Ethernet; 1 Gbps; 100m 
        -10 Gig Ethernetl  10 Gbps; 55m 

    CAT 7,
        -10 Gig Ethernet; 10 Gbps; 100m 

    CAT 8,  


*Fiber Cables 

    SMF, (Single Mode Fiber)
        -travels far 6miles 
        

    MMF, (Multimode Fiber) 
        -shorter distance 550m 


*Types of Fyber Cables : 

    ST connector | Straight Tip| sort & twist 
    -These are older, used with MMF 


    SC connector | Sibscriber Connector | short and chunky 
    -used with SMF and MMF 
    -Common in data centers & telecom 

    LC connector | Lucent Connector
    -Smaller/compact version of SC 
    -Push/pull like SC but half the 


*Transceiver Types 
-These suffixes appear on fiber transceivers/SFPs \
-They tell you the speed, fiber type, and distance supported.

| Suffix | Stands For | Fiber Type | Speed | Distance |
|---|---|---|---|---|
| FX | Fast Ethernet | MMF (OM1) | 100 Mbps | ~2 km (2000 m) |
| SX | Short Wavelength | MMF (OM2/OM3) | 1 Gbps | ~220–550 m |
| LX | Long Wavelength | MMF / SMF | 1 Gbps | MMF: ~550 m / SMF: ~10 km |
| SR | Short Range | MMF (OM3/OM4) | 10 Gbps | ~300–400 m |
| LR | Long Range | SMF (OS1/OS2) | 10 Gbps | Up to 10 km |

### Key Takeaways
- **MMF** = shorter distances, used inside buildings (OM1–OM4)
- **SMF** = longer distances, used between buildings/cities (OS1/OS2)
- **S prefix** (SX, SR) = short = MMF
- **L prefix** (LX, LR) = long = SMF (or both)
- Higher speed (10 Gbps) requires newer fiber grades (OM3/OM4 or OS1/OS2)


*Carrier Sense Multiple Acccess with Collision Detection (CSMA/CD)
-relevant to Hubs, not switches (half duplex hub based connectors) 
-regulates communications in networks with shared transmission mediums. 
-prevents collision of data 


*Relevance of knowing OSI Layer
    -Helps with trouble shooting network issues 
    -All people seem to need Data Processing
    -from phyical -> transport is networking's problem 



































 -->






























## Learning labs (Flex)





## Video & Their Questions  



## At Home Graded Labs



## Study Guide Notes 



## Final Exam Review



## Homework Assingment  