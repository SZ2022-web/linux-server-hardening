# 🛡️ Linux Server Hardening Lab

## 📌 Project Overview
This project demonstrates how to secure a Linux system by applying industry-standard hardening techniques. It focuses on system updates, user management, firewall rules, SELinux, and logging.

## ⚙️ Lab Environment
- **OS:** Ubuntu 22.04 LTS / RedHat 9 (VM)
- **Tools:** firewalld, SELinux, auditd, fail2ban, ssh

## 📝 Steps Performed
### 1) System Updates
```bash
sudo apt update && sudo apt upgrade -y
