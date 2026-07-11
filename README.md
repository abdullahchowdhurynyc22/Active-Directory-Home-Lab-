
# Active Directory Home Lab Project

## Project Overview
This project demonstrates the deployment, configuration, and administration of an enterprise Active Directory (AD) environment using Windows Server 2025 and a Windows 11 client workstation. 

The lab simulates real-world enterprise IT support tasks and replicates a small company network architecture utilizing a pfSense firewall, Windows Server infrastructure, and client operating systems.

---

## Key Skills Demonstrated
* Active Directory deployment and domain controller promotion
* DNS configuration (forward/reverse lookup zones)
* Organizational Unit (OU) design and structural hierarchy
* Security group management and Role-Based Access Control (RBAC)
* User lifecycle management (provisioning and deprovisioning)
* Domain authentication and joining client workstations
* File share permission management using NTFS and SMB

---

## Lab Architecture

### Network Specifications
* Domain Name: lab.local
* Subnet: 192.168.10.0/24

### Device Inventory
| Device Name | Operating System | IP Address | Role / Function |
| :--- | :--- | :--- | :--- |
| pfSense | pfSense Firewall | 192.168.10.1 | Default Gateway, DHCP, Network Isolation |
| DC01 | Windows Server 2025 | 192.168.10.20 | Domain Controller, DNS Server, AD DS |
| WIN11-CLI | Windows 11 | 192.168.10.10 | Enterprise Client Workstation |
| UBUNTU-SRV | Ubuntu Server | 192.168.10.30 | Linux Server Member |
| UBUNTU-DSK | Ubuntu Desktop | 192.168.10.40 | Linux Client Workstation |

---

## Technologies Used
* Active Directory Domain Services (AD DS)
* DNS, File and Storage Services (SMB/NTFS)
* Windows Server 2025, Windows 11, Ubuntu Linux
* pfSense Firewall
* UTM Virtualization



## Screenshots

### Domain Controller Setup
![Domain Controller Setup](path/to/screenshot1.png)

### Organizational Unit Structure
![Organizational Unit Structure](path/to/screenshot2.png)

### Domain Join
![Domain Join](path/to/screenshot3.png)

### Domain User Login
![Domain User Login](path/to/screenshot4.png)

### File Share Access Test
![File Share Access Test](path/to/screenshot5.png)
