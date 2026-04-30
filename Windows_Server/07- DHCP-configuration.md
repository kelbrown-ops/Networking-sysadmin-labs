# DHCP Configuration (Windows Server 2025)
## Overview

In this lab, I installed and configured Dynamic Host Configuration Protocol (DHCP) on Windows Server 2025 to automatically assign IP addresses to client machines in the network.

## Objective
- Install DHCP Server role
- Configure a DHCP scope
- Enable automatic IP address assignment

  
## Configuration Steps
### 1. Installing DHCP Server Role
- Opened Server Manager
- Clicked Add Roles and Features
- Selected DHCP Server
- Completed installation

![dhcp-feature](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/dhcp-configuration/dhcp-feature.png)

### 2. Authorizing DHCP Server
- Opened DHCP Management Console
- Authorized the DHCP server in Active Directory

![dhcp-authorisation](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/dhcp-configuration/dhcp-authorisation.png)

### 3. Creating a New Scope
- Right-clicked on IPv4 → New Scope
- Entered scope name

![scope-name](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/dhcp-configuration/scope-name.png)

### 4. Configuring IP Range
- Defined IP address range:
- Start IP: (e.g., 192.168.1.100)
- End IP: (e.g., 192.168.1.200)
- Subnet Mask: (e.g., 255.255.255.0)

![ip-range](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/dhcp-configuration/ip-range.png)

### 5. Configuring Gateway and DNS
- Added default gateway (router/server IP)


### 6. Activating the Scope
- Activated the DHCP scope
- Verified it is running


### 7. Testing DHCP Assignment
- Set client machine to obtain IP automatically
- Ran:
- ipconfig /renew
- Verified assigned IP from DHCP range

![verified-dhcp](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/dhcp-configuration/verified-dhcp.png)

## What I Learned
- How DHCP automates IP address assignment
- Importance of scopes in network management
- Integration of DHCP with DNS and Active Directory
## Next Steps
- Configure DNS Server
- Integrate DHCP with domain environment
- Monitor DHCP leases
## Final Thoughts

- DHCP simplifies network management by automating IP assignment, making it essential for scalable and efficient network environments.
