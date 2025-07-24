# 🐧 Linux Configuration & Security

This folder contains essential Linux system administration and security configuration practice files.

It includes logs, command outputs, and config snippets from real virtual machine experiments (Debian/Ubuntu-based).

## 🧰 Covered Topics

- User account management (adduser, sudo, groups)
- File and directory permissions (chmod, chown)
- SSH hardening and firewall setup (ufw, iptables)
- FTP setup and secure connections
- Service management and monitoring

## 💡 Objectives

- Build comfort with terminal-based system management
- Learn to secure a basic Linux server
- Document best practices for system admins and security analysts
## ⚙️ Commands Used

```bash
sudo apt update
sudo apt install ufw
sudo ufw enable
sudo ufw allow ssh
sudo ufw allow 80/tcp
sudo ufw status verbose

🔒 Outcome
1-Enabled default deny policy

2-Allowed SSH and HTTP

3-Verified status with detailed output
