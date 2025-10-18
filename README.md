🧰 Active Directory Site & Replication Setup (Windows Server 2022)
📘 Project Overview
This project demonstrates how to configure multiple Active Directory sites and manage replication between them — simulating a multi-office enterprise environment (e.g., London HQ and Manchester Branch).
🧠 Objectives
Configure multiple AD sites using Active Directory Sites and Services
Establish site links and manage replication schedules
Verify replication using repadmin and PowerShell
🖥️ Environment Setup
Component	Description
OS	Windows Server 2022
Domain Name	itservices.local
Site A	London-HQ (DC01)
Site B	Manchester-Branch (DC02)
Client Machine	Windows 10 (joined to domain)
⚙️ Steps Implemented
Installed AD DS and DNS on DC01
Created domain itservices.local
Joined DC02 to domain
Promoted DC02 to domain controller
Created two AD Sites: London-HQ and Manchester-Branch
Configured Site Links and replication schedules
Verified replication with PowerShell commands
🧩 PowerShell Verification
repadmin /replsummary
repadmin /showrepl
📸 Screenshots
Step	Description	Screenshot
1	DC01 setup with AD DS & DNS	
2	DC02 joined to domain	
3	AD Sites created	
4	Site Link configuration	
5	Replication schedule	
6	Repadmin replication summary	
🧱 Key Learning Points
How AD replication topology supports distributed environments
The role of site cost and scheduling in optimizing bandwidth
Verification and troubleshooting of replication status
