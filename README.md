# Ansible LAMP/LEMP Stack Deployment

## 📌 Project Overview

This project automates the deployment of LAMP (Linux, Apache, MySQL/MariaDB, PHP) and LEMP (Linux, Nginx, MySQL/MariaDB, PHP) stacks on target servers using Ansible.  
It is designed to help system administrators and DevOps engineers quickly provision and configure web servers for hosting dynamic websites and web applications.

---

## 🚀 Features

- ✅ Automated installation and configuration of:
  - Apache or Nginx web server
  - MySQL/MariaDB database server
  - PHP with required modules
- ✅ Idempotent Ansible playbooks for repeatable deployments
- ✅ Variables to choose between LAMP and LEMP stacks
- ✅ Secure configuration (firewall rules, user permissions)
- ✅ Tested on Ubuntu and CentOS servers

---

## 📂 Project Structure

Ansible_LAMP_LEMP_Stack/
├── inventory.ini
├── playbook.yml
├── roles/
│ ├── common/
│ ├── apache/
│ ├── nginx/
│ ├── mysql/
│ └── php/
└── README.md


- `inventory.ini` — Inventory file with your target hosts.
- `playbook.yml` — Main Ansible playbook.
- `roles/` — Contains reusable roles for modular deployment.

---

## ⚙️ Prerequisites

- Ansible installed on your control node.
- SSH access to target servers with sudo privileges.
- Target servers running Linux (Ubuntu/CentOS).
- Updated SSH keys for passwordless access.

