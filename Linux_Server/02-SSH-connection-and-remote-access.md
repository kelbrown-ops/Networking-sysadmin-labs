# Linux Server Administration – SSH Connection & Remote Access

## Overview

In this lab, I established a remote connection to my Linux server using SSH from a Windows client machine. Due to issues with the native SSH command-line tool, I used PuTTY to successfully connect.

---

## 🎯 Objective

* Enable remote access to the Linux server
* Connect securely from a Windows machine
* Verify SSH service functionality

---

## 🛠️ Configuration Steps

### 1. Verifying SSH Service on Server

* Checked SSH service status:

  ```
  sudo systemctl status ssh
  ```
* Confirmed that the SSH service was running

---
![ssh_service_status](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/Linux_Server/linux_screenshots/ssh_configuration_and_access/ssh_status_2.png)
### 2. Identifying Server IP Address

* Retrieved IP address using:

  ```
  ip a
  ```
* Noted the active network interface IP

---
![server_ip_address](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/Linux_Server/linux_screenshots/ssh_configuration_and_access/ip_address.png)
### 3. Attempting SSH via Command Prompt

* Tried connecting using:

  ```
  ssh username@server-ip
  ```
* Encountered error:
  *“ssh is not recognized as an internal or external command”*

---
![ssh_failure](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/Linux_Server/linux_screenshots/ssh_configuration_and_access/ssh_failure.png)
### 4. Using PuTTY for SSH Connection

* Installed and launched PuTTY
* Entered server IP address
* Set connection type to SSH (port 22)
* Initiated connection

---
![ssh_connect](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/Linux_Server/linux_screenshots/ssh_configuration_and_access/ssh_connect.png)
### 5. Establishing Connection

* Accepted security/host key prompt
* Entered Linux server username and password
* Successfully logged into the server

---
![ssh_successful](https://github.com/kelbrown-ops/Networking-sysadmin-labs/blob/main/Linux_Server/linux_screenshots/ssh_configuration_and_access/ssh_successful.png)
## ⚠️ Challenges Encountered

* Native SSH command not available on Windows
* Resolved by using PuTTY as an alternative SSH client

---

## 📚 What I Learned

* SSH is essential for remote server administration
* Multiple tools (CLI and GUI) can be used to establish SSH connections
* Understanding alternatives like PuTTY is important in real-world scenarios

---



## 🚀 Next Steps

* Create and manage users
* Configure file permissions
* Implement access control

---

## 💭 Final Thoughts

Establishing remote access using SSH is a critical skill in system administration. While command-line tools are commonly used, alternative tools like PuTTY provide reliable access when native tools are unavailable or misconfigured.
