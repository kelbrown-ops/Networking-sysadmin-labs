# File Server Configuration & Shared Folder Setup
## Overview

In this lab, I configured file sharing on Windows Server 2025 to allow network users to access shared resources.

## Objective
- Create a shared folder
- Configure permissions
- Enable network access for users
## Configuration Steps
### 1. Creating a Shared Folder
- Created a new folder (e.g., Shared_folder)
- Located on local disk

![shared_folder](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/file-server/shared_folder.png)

### 2. Configuring Share Permissions
- Right-clicked folder → Properties → Sharing
- Clicked Advanced Sharing
- Enabled Share this folder

![share_enabled](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/file-server/share-enabled.png)

### 3. Setting Permissions
- Added users/groups
- Assigned permissions: Read/Write (as needed)

![added-group](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/file-server/added-group.png)

### 4. Configuring NTFS Permissions
- Navigated to Security tab
- Adjusted access control for users

![NTFS-permissions](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/file-server/NTFS-permissions.png)

### 5. Accessing Shared Folder from Client
- On client machine, opened Run:
\\server-name\SharedFiles

![folder-path](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/file-server/folder-path.png)

- Verified access

![verified-access](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/images/file-server/verified-access.png)


## What I Learned
- Difference between share and NTFS permissions
- How to control access to network resources
- Importance of file servers in organizations
## Next Steps
- Configure Shadow Copies
- Implement backup and recovery
- Manage user access more strictly
## Final Thoughts

- File sharing is a core function in network environments, allowing centralized storage and controlled access to resources.
