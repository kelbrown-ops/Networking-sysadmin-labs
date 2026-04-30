# Linux Server Administration – SSH Connection & Remote Access

## Overview

In this lab, I established a remote connection to my Linux server using SSH from a Windows client machine.

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
![ssh_service_status]
### 2. Identifying Server IP Address

* Retrieved IP address using:

  ```
  ip a
  ```
* Noted the active network interface IP

---

### 3. Preparing Windows Client

* Attempted SSH connection via Command Prompt
* Encountered error: SSH not recognized
* Installed OpenSSH Client on Windows

---

### 4. Establishing SSH Connection

* Connected using:

  ```
  ssh username@server-ip
  ```
* Accepted host key verification
* Entered user password

---

### 5. Successful Remote Login

* Gained terminal access to the Linux server from Windows
* Verified full remote control capability

---

## ⚠️ Challenges Encountered

* SSH command not recognized on Windows
* Resolved by installing PuTTY on client machine

---

## 📚 What I Learned

* SSH is essential for remote server management
* Windows requires OpenSSH Client for terminal-based connections
* Network configuration must allow both machines to communicate

---

## 📸 Screenshots

(Add your screenshots here)

* SSH service status on server
* IP address output (`ip a`)
* Windows error (SSH not recognized)
* OpenSSH Client installation
* Successful SSH login

---

## 🚀 Next Steps

* Create and manage users
* Configure file permissions
* Implement access control

---

## 💭 Final Thoughts

SSH provides a secure and efficient way to manage servers remotely. Establishing a working SSH connection is a fundamental step in real-world system administration.
