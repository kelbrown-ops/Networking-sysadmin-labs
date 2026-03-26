# File Server Configuration & Shared Folder Setup
## Overview

In this lab, I configured file sharing on Windows Server 2025 to allow network users to access shared resources.

## Objective
- Create a shared folder
- Configure permissions
- Enable network access for users
## Configuration Steps
### 1. Creating a Shared Folder
- Created a new folder (e.g., SharedFiles)
- Located on local disk

### 2. Configuring Share Permissions
- Right-clicked folder → Properties → Sharing
- Clicked Advanced Sharing
- Enabled Share this folder

### 3. Setting Permissions
- Added users/groups
- Assigned permissions (Read/Write as needed)

### 4. Configuring NTFS Permissions
- Navigated to Security tab
- Adjusted access control for users

### 5. Accessing Shared Folder from Client
- On client machine, opened Run:
\\server-name\SharedFiles
- Verified access

## Challenges Encountered
(Add issues or: “No major issues encountered”)
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
