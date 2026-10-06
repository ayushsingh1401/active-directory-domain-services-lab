# Active Directory Domain Services (AD DS) — IT Support Lab

![Windows Server](https://img.shields.io/badge/Windows%20Server-AD%20DS-blue)
![Active Directory](https://img.shields.io/badge/Active%20Directory-Domain%20Services-green)
![DNS](https://img.shields.io/badge/DNS-Configured-orange)
![VirtualBox](https://img.shields.io/badge/VirtualBox-Lab-red)
![Windows 11](https://img.shields.io/badge/Client-Windows%2011-blue)

## 📌 Project Overview

This project is a hands-on Active Directory Domain Services (AD DS) laboratory environment built to develop practical Windows administration and IT Support skills.

The lab simulates a small enterprise Windows domain environment consisting of:

- A Windows Server acting as the Domain Controller
- Active Directory Domain Services (AD DS)
- DNS services
- A Windows 11 client machine
- Domain users and computer accounts
- Domain authentication
- Basic permissions and access management
- Network and Active Directory troubleshooting

The primary goal of this project is to understand how centralized user, computer, authentication, and access management works in a Windows domain environment.

---

# 🎯 Project Objectives

The main objectives of this project were:

- Install and configure Windows Server
- Configure a Windows Server as a Domain Controller
- Install Active Directory Domain Services
- Create an Active Directory domain
- Configure DNS for the Active Directory environment
- Create and manage domain user accounts
- Configure a Windows client machine
- Configure client DNS settings
- Join a Windows client to the domain
- Authenticate using domain credentials
- Understand computer accounts in Active Directory
- Understand Organizational Units (OUs)
- Understand security groups and permissions
- Practice Active Directory troubleshooting
- Develop a structured IT Support troubleshooting methodology

---

# 🏗️ Lab Architecture

The laboratory environment consists of two virtual machines running inside Oracle VirtualBox.

```text
                    Active Directory Domain
                           |
                           |
                 +-----------------------+
                 |   Windows Server      |
                 |                       |
                 |  Domain Controller     |
                 |  AD DS                |
                 |  DNS                  |
                 +-----------------------+
                           |
                           |
                    Virtual Network
                           |
                           |
                 +-----------------------+
                 |   Windows 11 Client   |
                 |                       |
                 |  Domain Joined        |
                 |  Domain User Login     |
                 +-----------------------+
