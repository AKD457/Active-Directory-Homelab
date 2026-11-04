Active Directory Homelab

Overview
Built a Windows Server 2022 Active Directory homelab using Hyper-V to simulate a small business environment.

Technologies
Windows Server 2022
Active Directory Domain Services
DNS
Group Policy
Hyper-V
Windows 11
WireGuard
PowerShell
Environment
DC01
Roles:

Active Directory
DNS
FILE01
Roles:

File Server
Shared Storage
CLIENT01
Roles:

Domain Joined Workstation
AD Structure
CORP ├── Users ├── Groups ├── Computers ├── Servers ├── IT ├── HR └── Service Accounts

Security Groups
IT_Admins
HR_Users
File_RW
File_RO
Domain_Workstations
Testing Performed
Domain join validation
RBAC testing
Group Policy deployment
Share permissions testing
Remote administration via WireGuard
Lessons Learned
DNS is critical to Active Directory functionality
Hyper-V Enhanced Session Mode can impact domain user logins
Security groups provide scalable access control
Group Policy can be used to centrally manage workstations
