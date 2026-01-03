# Active Directory Home Lab 💻

## Overview
This project is a **hands-on Active Directory home lab** built using **Windows Server 2019** and a **Windows 10 client VM** in **Oracle VirtualBox**.  
It follows a guided tutorial to simulate a small enterprise environment, demonstrating **domain services, core networking, and user management**.

This lab highlights foundational skills relevant to **IT support, system administration, and identity management**.

---

## Environment
- **Virtualization:** Oracle VirtualBox  
- **Server OS:** Windows Server 2019 (Desktop Experience)  
- **Client OS:** Windows 10 (64-bit)  
- **Services Configured:**  
  - Active Directory Domain Services (AD DS)  
  - DNS  
  - DHCP  
  - Routing and Remote Access (RAS / NAT)  

---

## Lab Objectives
- Install and configure Windows Server in a virtualized environment  
- Deploy **Active Directory Domain Services** and promote the server to a Domain Controller  
- Configure **core network services** (RAS/NAT, DHCP) for client connectivity  
- Create **Organizational Units (OUs)** and domain user accounts  
- Automate bulk user creation using **PowerShell**  
- Join a Windows client to the domain and verify authentication  

---

## Lab Steps

### 1. Windows Server Installation
Installed Windows Server 2019 with Desktop Experience on a VirtualBox VM and prepared it for domain services.

### 2. Active Directory Domain Services (AD DS) Installation
Installed AD DS and DNS roles to enable centralized authentication and domain management.

### 3. Domain Controller Promotion
- Created a new Active Directory domain (e.g., `mydomain.com`)  
- Promoted the server to a **Domain Controller**  
- Verified domain creation and functionality  

### 4. RAS / NAT Configuration
- Enabled **Routing and Remote Access**  
- Configured **NAT** to allow the Windows 10 client VM internet access and internal network communication  

### 5. DHCP Server Configuration
- Installed the DHCP Server role  
- Created and configured a **DHCP scope** (IP range, subnet mask, gateway)  
- Authorized the DHCP server in Active Directory  
- Verified client IP assignment  

### 6. PowerShell Bulk User Creation
- Executed a **PowerShell script** to automatically generate multiple domain user accounts  
- Created users within Organizational Units  
- Verified successful creation in **Active Directory Users and Computers (ADUC)**  

### 7. Windows Client Domain Join and Authentication
- Joined the Windows 10 VM to the Active Directory domain  
- Verified domain membership and authentication using `whoami /fqdn`  

---

## Screenshots

### 1. AD DS Installed
Shows Active Directory Domain Services and DNS installed on the server.  
![AD DS Installed](https://github.com/user-attachments/assets/5b7fdbe0-d3cd-4e36-a73a-8a26c7d51586)

---

### 2. Domain Controller Promoted
Shows the server successfully promoted to a Domain Controller and the domain created.  
![Domain Controller Promotion](https://github.com/user-attachments/assets/bb4a0951-48b9-4e39-9765-669f96a38444)

---

### 3. RAS / NAT Configuration
Displays the Routing and Remote Access console with NAT enabled and internal/external interfaces configured.  
<img width="1694" height="1011" alt="RAS-NAT-CONFIGURED" src="https://github.com/user-attachments/assets/25a8b350-088a-4766-b8cb-7784817abfb3" />

---

### 4. DHCP Server Scope Created
Shows the DHCP Management Console with an authorized scope configured for the domain network.  
<img width="1570" height="816" alt="DHCP-SERVER-SCOPE" src="https://github.com/user-attachments/assets/17d6a336-946d-4773-bd59-1a7b6bb151b5" />

---

### 5. PowerShell Bulk User Creation
Displays PowerShell output confirming successful bulk user creation, along with ADUC showing OUs and domain users.  
<img width="1909" height="976" alt="POWERSHELL-BULK-USER-CREATION" src="https://github.com/user-attachments/assets/863e4774-9e26-4661-90eb-37ad5fae351d" />

---

### 6. Windows Client Joined to Domain
Confirms the Windows 10 client is joined to the domain (`mydomain.com`) and received an IP address from DHCP.  
<img width="1304" height="888" alt="WCLIENT-JOINED-DOMAIN" src="https://github.com/user-attachments/assets/bbcb7c84-3098-4a98-8f4b-d0e42e77d64c" />

---

## Skills Demonstrated
- Windows Server installation and configuration  
- Active Directory Domain Services (AD DS) and DNS  
- RAS / NAT and DHCP network configuration  
- Organizational Unit and domain user management  
- PowerShell scripting for automation  
- Domain join and authentication verification  
- Virtualization using Oracle VirtualBox  
- Technical documentation for IT projects  

---

## Career Relevance
This lab reflects real-world **entry-level IT support and systems administration responsibilities**, including network services, user provisioning, and identity management.

Skills demonstrated are applicable to:
- IT Support / Help Desk Technician  
- Junior Systems Administrator  
- Network Administrator  
- Cybersecurity and Identity & Access Management roles  
