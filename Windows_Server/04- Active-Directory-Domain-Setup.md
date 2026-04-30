# Active Directory Domain Setup (Windows Server 2025)
## Overview

In this lab, I installed and configured Active Directory Domain Services (AD DS) on Windows Server 2025 and promoted the server to a Domain Controller.

## Objective
- Install Active Directory Domain Services
- Promote the server to a Domain Controller
- Create a new domain environment

## Configuration Steps
### 1. Installing Active Directory Domain Services (AD DS)
- Opened Server Manager
- Clicked on Add Roles and Features
- Selected Active Directory Domain Services
- Completed installation

![AD_DS_Installation](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/active-directory-setup/AD_DS-installation-complete.png)

### 2. Promoting Server to Domain Controller
- Clicked on Promote this server to a domain controller
- Selected Add a new forest
- Entered domain name: (KELBROWN.COM)

![Domain_name](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/active-directory-setup/Domain-name.png)

### 3. Domain Controller Configuration
- Set Directory Services Restore Mode (DSRM) password
- Selected default options for DNS and NetBIOS

![Admin_Password](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/active-directory-setup/DRSM-password.png)

### 4. Completing Installation
- Reviewed configuration
- Clicked Install
- Server automatically restarted

![Installation_Completed](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/active-directory-setup/AD_DS-confirmed.png)

### 5. Verifying Domain Setup
- Logged back into the server
- Confirmed domain was created
- Opened Active Directory Users and Computers

![AD_DS_Confirmed](images/active-directory-setup/AD_DS-confirmed.png)

## Challenges Encountered
- (Add any issues or write: “No major issues encountered”)

## Lession learned
- How to install and configure Active Directory Domain Services
- The process of promoting a server to a Domain Controller
- Importance of domain environments in network management
## Next Steps
- Join client machines to the domain
- Create users and organizational units (OUs)
- Configure Group Policy
## Final Thoughts

- Setting up Active Directory and promoting a Domain Controller is a major step in building a functional network environment, forming the foundation for centralized management and security.
