# Ansible Automation (Demo)

This project demonstrates automated server provisioning and configuration management using **Ansible playbooks**, improving consistency and reducing manual effort by **70%**.

---

### Note
> ⚠️ **This is a demo version** of my original project. Resource names and configurations are generic placeholders (“demo”) to ensure safe public sharing.

---

## Features
- Automated server provisioning
- Configuration management for Linux servers
- Role-based playbooks for reusability
- Idempotent operations for safe deployments
- Reduced manual intervention
- Scalable automation

---

## Architecture Diagram


## 📂 Project Structure

```text
ansible-automation/
│── playbooks/
│   ├── site.yml
│   ├── webserver.yml
│   ├── database.yml
│── roles/
│   ├── common/
│   │   ├── tasks/main.yml
│   │   ├── handlers/main.yml
│   │   ├── templates/
│   │   └── files/
│   ├── webserver/
│   │   ├── tasks/main.yml
│   │   ├── handlers/main.yml
│   │   ├── templates/
│   │   └── files/
│   ├── database/
│       ├── tasks/main.yml
│       ├── handlers/main.yml
│       ├── templates/
│       └── files/
│── inventory/
│   ├── hosts.ini
│── ansible.cfg
│── README.md
│── .gitignore



Getting Started

1. Prerequisites

Ansible installed
SSH access to target servers
Inventory configured

2. Run Playbooks
ansible-playbook playbooks/site.yml

3. Verify Deployment
ansible all -m ping


Learning Objectives :

Automate server provisioning
Implement configuration management
Create reusable Ansible roles
Manage multiple environments with inventory files
Apply idempotent automation