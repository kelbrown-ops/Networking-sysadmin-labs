# Client Machine Joined to Domain (Windows Server 2025)
## Overview

In this lab, I joined a Windows client machine to a domain created using Windows Server 2025 Active Directory Domain Services.

## Objective
- Connect a client machine to the domain
- Enable centralized authentication
- Verify communication between client and Domain Controller

## Configuration Steps
### 1. Configuring Client Network Settings
- Ensured client machine was on the same network as the server
- Set DNS server to point to the Domain Controller
- IP Address: (e.g., 192.168.1.11)
- DNS Server: (Server IP, e.g., 192.168.1.10)

### 2. Accessing System Settings
- Opened System Properties
- Clicked on Change settings under computer name

### 3. Joining the Domain
- Selected Domain option
- Entered domain name: (your domain, e.g., lab.local)
- Clicked OK

### 4. Authentication
- Entered domain administrator credentials
- Successfully authenticated

### 5. Restarting the Client
- Restarted the client machine to apply changes
### 6. Verifying Domain Join
- Logged in using a domain account
- Confirmed successful domain connection

## Challenges Encountered
- (Add issues or: “No major issues encountered”)
## What I Learned
- How domain-based authentication works
- Importance of DNS configuration in domain environments
- Process of integrating client machines into Active Directory
## Next Steps
- Create domain users and groups
- Set up Organizational Units (OUs)
- Apply Group Policies
## Final Thoughts

- Joining a client machine to a domain demonstrates how centralized management works in real-world network environments, enabling efficient control over users and systems.
