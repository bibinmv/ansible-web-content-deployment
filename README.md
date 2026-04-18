# Automated Web Content Deployment using Ansible (RHEL 9)

## 📌 Overview
This project automates the deployment of a web server and web content using Ansible on Red Hat Enterprise Linux 9.

## 🚀 Features
- Automated Apache (httpd) installation and configuration
- Firewall configuration using Ansible (firewalld)
- Secure directory setup with group permissions (setgid)
- SELinux context management
- Symbolic link integration with web root
- Idempotent playbook execution

## 🧰 Technologies Used
- Ansible
- RHEL 9
- Apache (httpd)
- Firewalld
- SELinux

## 📁 Project Structure


## ⚙️ Setup Instructions

1. Install Ansible on control node
2. Configure SSH access to managed nodes
3. Update inventory file with target hosts

## ▶️ Run Playbook

```bash
ansible-playbook -i inventory webcontent.yml
---
Verification

curl http://<node>/webdev/


Expected output:

Development


