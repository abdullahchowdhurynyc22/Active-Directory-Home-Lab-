
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
<img width="672" height="419" alt="Image" src="https://github.com/user-attachments/assets/9cec4421-f924-40bf-95df-14d72c19a2a5" />

### Organizational Unit Structure
<img width="672" height="483" alt="Image" src="https://github.com/user-attachments/assets/6936d696-6d67-425b-ae55-0f0a7c7223e8" />

### Domain Join
<img width="648" height="671" alt="Image" src="https://github.com/user-attachments/assets/562439be-22eb-48bb-94bb-33317b926d09" />

### Domain User Login

<img width="671" height="415" alt="Image" src="https://github.com/user-attachments/assets/6dae28e7-86e2-462a-9eb9-6d1a8f8c4be1" />

### File Share Access Test

<img width="672" height="264" alt="Image" src="https://github.com/user-attachments/assets/da1050ac-06e8-4755-8466-102e03f300ec" />
