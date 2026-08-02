# Active-Directory-Home-Lab
A hands-on Active Directory home lab built using Windows Server 2016 and VMware. This project demonstrates Domain Controller installation, DNS configuration, and Windows Server administration.

# Active Directory Home Lab

## Overview

This project demonstrates the installation and configuration of Microsoft Active Directory Domain Services (AD DS) on Windows Server 2016. The goal of this lab was to gain hands-on experience with Windows Server administration and understand how organizations manage users, computers, authentication, and security through Active Directory.

This project was completed in my home lab using VMware.

---

## Objectives

- Install Windows Server 2016
- Install Active Directory Domain Services (AD DS)
- Promote the server to a Domain Controller
- Create a new Active Directory forest
- Configure DNS
- Verify successful Active Directory installation
- Document every step of the deployment process

---

## Technologies Used

- Windows Server 2016
- VMware Workstation
- Active Directory Domain Services
- DNS Server
- Server Manager

---

## Skills Demonstrated

- Windows Server Administration
- Active Directory Installation
- Domain Controller Deployment
- DNS Configuration
- Windows Server Roles and Features
- Troubleshooting
- Technical Documentation

---

## Installation Process

1. Installed Windows Server 2016 Desktop Experience.
2. Opened Server Manager.
3. Added the Active Directory Domain Services role.
4. Installed the required features.
5. Promoted the server to a Domain Controller.
6. Created a new Active Directory forest.
7. Configured DNS.
8. Completed prerequisite checks.
9. Restarted the server.
10. Verified Active Directory installation.

---

## Challenges

During installation I encountered a prerequisite error because the local Administrator account had no password.

To resolve the issue, I created a strong Administrator password and reran the prerequisite check. The installation completed successfully afterward.

This helped me understand why Windows Server requires secure credentials before promoting a server to a Domain Controller.

---

## Screenshots

Screenshots of each stage of the installation are available in the screenshots folder.

---

## Demo Video

A demonstration video explaining the installation process is included in this repository.

---

## What I Learned

Through this project I learned:

- How Active Directory works
- The purpose of a Domain Controller
- How DNS integrates with Active Directory
- How to promote a Windows Server into a Domain Controller
- How to troubleshoot Active Directory installation issues

---

## Future Improvements

In the next project I will:

- Create Organizational Units (OUs)
- Create Users and Groups
- Join Windows clients to the domain
- Configure Group Policy Objects (GPOs)
- Configure Shared Folders and Permissions

---

## Author

Chidera Okorie
