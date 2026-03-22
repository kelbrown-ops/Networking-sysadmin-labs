# Static IP Configuration (Windows Server 2025)
## Overview

In this lab, I configured a static IP address on Windows Server 2025 to ensure consistent network communication within my lab environment.

### Objective

- Assign a static IP address to the server

- Ensure stable and predictable network connectivity

- Prepare the server for roles like DNS and Active Directory

## Configuration Steps
### 1. Accessing Network Settings

- Opened Server Manager

- Navigated to Local Server

- Clicked on the network interface

### 2. Opening Adapter Properties

- Selected the active network adapter

- Opened Properties

- Selected Internet Protocol Version 4 (IPv4)

### 3. Assigning Static IP

- Selected Use the following IP address

- Entered the following details:

- IP Address: (your IP, e.g., 192.168.1.10)
  Subnet Mask: (e.g., 255.255.255.0)
  Default Gateway: (e.g., 192.168.1.1)
  Preferred DNS: (e.g., 8.8.8.8 or your server IP)

### 4. Applying Settings

- Clicked OK to save configuration

- Closed all network windows

### 5. Verifying Configuration

- Opened Command Prompt

- Ran: ipconfig

   

- Confirmed the static IP was assigned correctly

## Challenges Encountered

(Add any issue, or write: “No major issues encountered”)

## Lesson learned

- Difference between dynamic and static IP addressing

- Importance of static IPs in server environments

- How to manually configure network settings in Windows Server

## Next Steps

- Test connectivity using ping

- Configure DNS server

- Begin Active Directory setup

💭 Final Thoughts

- Configuring a static IP is a critical step in server setup, ensuring consistent communication and reliability in network environments.
