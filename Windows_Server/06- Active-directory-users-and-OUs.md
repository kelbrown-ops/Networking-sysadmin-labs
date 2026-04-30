# Active Directory Users & Organizational Units (OUs)
## Overview

In this lab, I created users and Organizational Units (OUs) in Active Directory on Windows Server 2025 to organize and manage network resources efficiently.

## Objective
- Create Organizational Units (OUs)
- Add domain users
- Understand structured user management
## Configuration Steps
### 1. Opening Active Directory Users and Computers
- Opened Server Manager
- Navigated to Tools → Active Directory Users and Computers

![tools](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/ad-users-ous/Tools.png)

### 2. Creating an Organizational Unit (OU)
- Right-clicked on the domain
- Selected New → Organizational Unit
- Created OU: (e.g., IT Department)

![IT-dept](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/ad-users-ous/created-ou.png)

### 3. Creating a New User
- Navigated into the OU
- Right-clicked → New → User
- Entered user details:
Username,
Full name,
Password.

![new-user](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/ad-users-ous/new-user.png)

### 4. Setting User Password Options
- Configured password settings:
- User must change password at next logon (optional)
- Password never expires (optional for lab)

![password](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/ad-users-ous/password-settings.png)

### 5. Verifying User Creation
- Confirmed the user appears in the OU
- Checked user properties

![user-confirmed](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/ad-users-ous/user-confirmed.png)

## Challenges Encountered
- No major issues encountered
## What I Learned
- How Organizational Units help structure a domain
- How to create and manage domain users
- Importance of organized user management in enterprise environments
## Next Steps
- Add users to groups
- Configure Group Policy (GPO)
- Test login with domain users
## Final Thoughts

- Creating OUs and users is essential for managing access and maintaining structure in a domain environment, especially in larger organizations.
