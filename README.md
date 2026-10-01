# Active Directory Homelab

This repository contains steps on how I set up a basic home lab running Active Directory. The aim of this homelab is to gain valuable hands-on experience with deploying and managing AD, DNS, GPOs, and security policies that can be used in an organization and tackle real life issues.I will build a fully simulated small enterprise environment.

## Learning Objectives

- Get hands-on with core AD administration skills relevant to IT Support / Network Admin roles
- Build a fully simulated small-enterprise domain environment: users, groups, OUs, GPOs, DNS/DHCP
- Learn to set up and manage a Domain Controller within a network infrastructure
- Develop problem-solving skills through troubleshooting any issues encountered during the setup and configuration process
- Acquire proficiency in using PowerShell scripting to automate administrative tasks within a Windows environment
- Produce a portfolio piece for job applications (IT Support Specialist / Network Technician / Junior Network Admin)

## Lab Environment

- Host Specs: 8 GB RAM, 256 GB SSD, 2 cores, 
- Domain Controller: 


## Lab Tasks


- Configure VirtualBox settings
- Install Windows Server 2022
- Rename server to SRV-DC01
- Configure static IP address
- Verify network connectivity
- Install Active Directory Domain Services
- Install DNS Server
- Create domain corp.alphalab.local
- Promote server to Domain Controller
- Verify domain functionality
- Create Company OU
- Create IT OU
- Create HR OU
- Create Finance OU
- Create Management OU
- Create Computers OU
- Create Servers OU
- Create Groups OU
- Create 15 user accounts
- Create IT_Users group
- Create HR_Users group
- Create Finance_Users group
- Managers group
- Add users to groups
- Reset a user password
- Disable a user account
- Enable a user account
- Unlock a locked account
- Delete a user account
- Restore a deleted account
- Install DHCP Server role
- Create DHCP scope
- Create DHCP reservation
- Create DHCP exclusion range
- Verify DHCP lease assignment
- Create DNS A record
- Create DNS CNAME record
- Create Reverse Lookup Zone
- Test DNS resolution
- Troubleshoot DNS issue
- Install Windows 10/11 client
- Connect client to corp-lan
- Join client to domain
- Log in with domain account
- Remove client from domain
- Rejoin client to domain
- Rename client to CLIENT01
- Create Password Policy GPO
- Create Account Lockout Policy GPO
- Create Desktop Wallpaper GPO
- Disable Control Panel via GPO
- Disable Command Prompt via GPO
- Create Drive Mapping GPO
- Force Group Policy update
- Create IT shared folder
- Create HR shared folder
- Create Finance shared folder
- Create Public shared folder
- Configure NTFS permissions
- Configure Share permissions
- Create hidden share
- Map shared drives
- Test user access permissions
- Simulate forgotten password ticket
- Simulate account lockout ticket
- Simulate DNS outage ticket
- Simulate DHCP failure ticket
- Simulate file access issue ticket
- Simulate domain join issue ticket
- Simulate printer issue ticket
- Document ticket resolution
- Create server build documentation
- Create Active Directory documentation
- Create Group Policy documentation
- Create DHCP documentation
- Create DNS documentation
- Create file server documentation
- Create asset inventory
- Create user inventory
- Create group inventory


## Key Skills

- Active Directory
- Windows Server
- DNS
- Group Policy
- PowerShell
- User & Group Management
- Network Administration
- Access Control
- Troubleshooting


## Repo Structure

/docs
01-server-install.md
02-domain-controller-setup.md
03-dns-dhcp-config.md
04-ou-users-groups.md
05-group-policy.md
06-client-join.md
/images
(screenshots referenced in docs)
README.md


## Key Terminologies

Active Directory: Active Directory is a directory service created by Microsoft that stores, manages info users, devices and resources over a network.

Active Directory Domain Services (AD DS): This is responsible for storing and managing information about users, services and devices connected to the network.

Domain Controller:

Organizational Units:

Group Policy Objects:

DNS: Domain Name Network is a phenomenon that resolves domain names. AD DS is heavily reliant on DNS to lcate the domain controller.

DHCP: Dynamic Host Configuration Protocol is a network protocol that assigns IP addresses automatically to devices over a network.

## Status

 In progress — started *29TH September 2026*
