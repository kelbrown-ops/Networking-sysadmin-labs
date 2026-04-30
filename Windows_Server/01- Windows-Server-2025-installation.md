# Windows Server 2025 Installation (Lab Setup)
---
## Overview

In this lab, I installed Windows Server 2025 on a virtual machine as part of my networking and system administration learning journey.


## Lab Environment

Virtualization Software: (VMware)

## Installation Steps
### 1. VM Creation

Created a new virtual machine

- RAM Allocated: (2GB)

- CPU: (2 cores)

- Storage: (16GB)

- Network Type: (Bridged)

- Attached the Windows Server 2025 ISO

![VM Setup](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/windows-server-installation/vm-setup.png)


### 2. Starting Installation

- Booted from ISO

- Selected language and regional settings

- Clicked "Install Now"

![Installation-starts](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/windows-server-installation/installation-starts.png)

### 3. Selecting OS Version

- Chose: ( Datacenter Evaluation)

- Selected (Desktop Experience)

![Select-Distribution](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/windows-server-installation/distribution-selection.png)

### 4. Disk Partitioning

- Selected storage disk

- Used default partition

![Disk-partitioning](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/windows-server-installation/disk-partition.png)

### 5. Installation Process

- Files copied and installed

- System restarted automatically

![installation-starts](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/windows-server-installation/installation-starts.png)

### 6. Initial Setup

- Set Administrator password

- Logged into the system

![Set-administrator-password](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/windows-server-installation/Setup-administrator-password.png)

### 7. Server Manager Interface
- This is where most the server configurations is done

  ![Server-Manager](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/windows-server-installation/Server-Manager-Interface.png)

## Challenges Encountered

- ISO file disk had wasn't loading properly so installation terminated on 2 attempts.


## What I Learned

- How to install Windows Server on a VM

- Importance of correct VM configuration

- Basic setup process for a server environment

## Next Steps

- Configure static IP

- Rename server

- Set up Active Directory

Final Thoughts

This was my first step in building a home lab environment for networking, system administration, and cybersecurity practice.
