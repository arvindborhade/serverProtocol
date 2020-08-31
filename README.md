# serverProtocol

Server Protocol

Server Ownership is under Project Manager / Tech Lead 

Server Architecture Ownership is under Infra Team 

Password Protocol:
1. AWS password is only shared to Project Manger / Tech Lead and Infra Team No need to share with Developers
2. Password need to strong 
3. Password need to Change after 3 months and Shared same with Infra Team on Mail 
4. If any Tech lead Left the Job, Infra team Need to Change password, and take all access from That Tech Lead of Project Manager



Any Changes in Server Are Categorise  in 3 Types 
    1. Minimal Level Change (Software Installation, Software Updates, Backup, Server Reboot)
    2. Medium Level Changes (Server Reboot, Server Shutdown, Server Start,Firewall Rules Update) 
    3. High Level Changes (Create New Server, Delete Old Server, Change in Server Architecture)

Procedure Cycle For Minimal Level Change 
1. Steps Taken Before Changes
    1. Backup of server
2. Approval Cycle
    1. Mail Approval From Project Manager/ Tech Lead CC to Infra Team
    2. Maintain Old Configuration And New Configuration in Mail 

Procedure Cycle For Medium Level Changes
1. Steps Taken Before Changes
    1. Backup of server
2. Approval Cycle
    1. Mail Approval From Project Manager/ Tech Lead CC 
    2. Approval From Infra Team
    3. Details Mail to Infra Team By Project Manager Before Approval 
        1. Reason for Changes / Action 
        2. Requested Person Name
        3. Approval Given By 
        4. Old Configuration 
        5. New Configuration/ New Changes

Procedure Cycle For High Level Changes
1. Steps Taken Before Changes
    1. Backup of server
2. Approval Cycle 
    1. Approval From Project Manager / Tech Lead
    2. Approval From Infra Team 
    3. Approval From Harshal 
    4. Details Mail to Infra Team By Project Manager For Approval 
        1. Reason for Changes / Action 
        2. Requested Person Name
        3. Approval Given By 
        4. Old Configuration 
        5. New Configuration/ New Changes
	


Minimal Level Changes Permitted to  Tech Lead / Project Manager

Medium Level Changes Permitted to Infra Team 

High Level Changes Permitted to do by Infra Team With Permission of Harshal 


List of Minimal Level Changes
1. Software Update
2. Software Installation 
3. Backup of Server
4. Server Reboot
5. — Adding More


List of Medium Level Changes
1. Server Shutdown
2. Server Start
3. Firewall Rules Update
4. — Adding More


List of High Level Change
1. Create New AWS Server 
2. Delete AWS Server 
3. Create New Architecture 
4. Update In Server Architecture 
5. Migrate Server to New Configuration  
6. — Adding More


