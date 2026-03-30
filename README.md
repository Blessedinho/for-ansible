# Ansible Server Setup Project

This project demonstrates how to automate basic server configuration using Ansible.

##  What This Playbook Does

- Creates a new user called `engineer`
- Assigns `/bin/bash` as the default shell
- Installs Nginx
- Starts the Nginx service
- Enables Nginx to start on boot

---

## 🖥️ Server Details

- Cloud Provider: AWS EC2
- OS: Ubuntu
- Connection: SSH using private key

---

## 📁 Files in This Project

### 1. inventory_file
Defines the target server


---

### 2. inventory_playbook.yml
Main Ansible playbook

---

## ⚙️ How to Run

```bash
ansible-playbook -i inventory.ini setup.yml


