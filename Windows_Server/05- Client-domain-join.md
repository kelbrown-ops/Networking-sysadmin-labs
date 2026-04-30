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
- IP Address: 192.168.1.2
- DNS Server: Server IP, 192.168.1.1

![ip-settings](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/domain-join/client-ip-settings.png)

### 2. Accessing System Settings
- Opened System Properties
- Clicked on Change settings under computer name

![client-name](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/domain-join/change-client-name.png)

### 3. Joining the Domain
- Selected Domain option
- Entered domain name: KELBROWN.COM
- Clicked OK

![enter-domain-name](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/domain-join/enter-domain-name.png)

### 4. Authentication
- Entered domain administrator credentials
- Successfully authenticated

![authentication](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/domain-join/authentication-successful.png)

### 5. Restarting the Client
- Restarted the client machine to apply changes


### 6. Verifying Domain Join
- Logged in using a domain account
- Confirmed successful domain connection

![verification](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/domain-join/verification.png)


## Challenges Encountered
- Testing connectivity between client and domain failed initially.

## What I Learned
- How domain-based authentication works
- Process of integrating client machines into Active Directory
## Next Steps
- Create domain users and groups
- Set up Organizational Units (OUs)
- Apply Group Policies
## Final Thoughts

- Joining a client machine to a domain demonstrates how centralized management works in real-world network environments, enabling efficient control over users and systems.
