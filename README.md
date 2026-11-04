# Active Directory Homelab

## Overview
This project builds a Windows Server 2022 Active Directory homelab using Hyper-V to simulate a small business environment. The lab is designed to model common enterprise identity, access control, and file-sharing practices found in real-world organizations.

## Technologies
- Windows Server 2022
- Active Directory Domain Services (AD DS)
- DNS
- Group Policy
- Hyper-V
- Windows 11
- WireGuard
- PowerShell

## Environment
The lab consists of three virtual machines:

### DC01
Roles:
- Active Directory
- DNS

### FILE01
Roles:
- File Server
- Shared Storage

### CLIENT01
Roles:
- Domain-joined workstation

## AD Structure
The Active Directory environment follows a simple corporate model:

```text
CORP
├── Users
├── Groups
├── Computers
├── Servers
├── IT
├── HR
└── Service Accounts
