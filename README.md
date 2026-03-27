# Enterprise Infrastructure Lab – Active Directory & Hyper-V

## Project Overview
This lab simulates a real-world enterprise IT infrastructure using Hyper-V and Windows Server 2022.

The goal was to build hands-on experience in system administration, identity management, and network services.

---

## Technologies Used
- Windows Server 2022
- Hyper-V
- Active Directory (AD DS)
- DNS
- DHCP
- Group Policy (GPO)

---

## Lab Architecture
- 1x Domain Controller (Windows Server 2022)
- 1x Client Machine (Windows 10/11)
- Internal Virtual Network (Hyper-V)

---

## Configuration Steps

### 1. Hyper-V Setup
- Created virtual machines
- Configured internal virtual switch
- Assigned static IP to server

### 2. Active Directory Setup
- Installed AD DS role
- Promoted server to Domain Controller
- Created domain (e.g., orbit.local)

### 3. DNS Configuration
- Configured DNS zone
- Verified name resolution

### 4. DHCP Configuration
- Created DHCP scope
- Assigned IP range to clients

### 5. User & Group Management
- Created users and security groups
- Assigned permissions

### 6. Group Policy (GPO)
- Configured password policies
- Applied restrictions to users

### 7. Client Join & Testing
- Joined client machine to domain
- Tested login authentication
- Verified network services

---

## Testing & Validation
- Domain login successful
- DHCP IP assignment verified
- DNS resolution tested
- GPO policies applied correctly

---

## Screenshots

### Active Directory Users & Computers
![AD Setup](screenshots/Active Directory Setup)

### DHCP Configuration
![DHCP](screenshots/dhcp.png)

### DNS Setup
![DNS](screenshots/dns.png)

### Domain Join
![Domain Join](screenshots/domain-join.png)

---

## Key Skills Demonstrated
- Active Directory Administration
- Windows Server Management
- DNS & DHCP Configuration
- Virtualization (Hyper-V)
- Troubleshooting Enterprise Environment

---

## Author
**Noor Hossain Anik**  
IT Support Analyst | Microsoft 365 | Active Directory | Intune | Networking | Systems Administrator
