# Ansible-Use-Cases
🔧 Ansible Automation – Post-Class Implementation Project
GBA 5200 | Adam Gomez & Zachary Martin

This project provides an overview of Ansible’s role in enterprise IT automation. It explains how to use Ansible for configuration management, application deployment, and network automation across distributed systems using agentless architecture.

🎥 Video Demonstration
Coming Soon: [YouTube Link or Upload]



💻 Environments and Technologies Used
Virtual Machines (e.g., Azure or local VM)

SSH: Used for secure remote execution

Linux / Unix systems (Ansible's primary target)

Windows (limited) for hosting virtualized environments or targets

🛠 Technologies Covered
Ansible Core & Architecture

YAML Playbooks

Ansible Modules, Roles, and Inventory

Ansible Automation Platform (AAP)

Push vs Pull Configuration Models

RBAC (Role-Based Access Control)

Security via SSH Keys

Ansible Galaxy & Collections

🧩 Project Scope
🔹 Agentless Architecture
Ansible operates without agents, using SSH to directly connect and execute commands across multiple nodes. This removes the overhead of maintaining software on each target.

🔹 YAML Playbooks & Modules
Configurations are defined in human-readable YAML files using modules like:

pip (Python dependencies)

openssh_cert

oci_vn (Oracle Cloud)

🔹 Playbook Structure
Inventory Files: Define target hosts/groups

Tasks & Roles: Modular automation logic

Reusability: Via pre-defined roles and collections

🔹 Automation Platform (AAP)
Enterprise-grade automation suite

Adds centralized web UI, monitoring, and RBAC

Suitable for large, hybrid IT environments

📈 Use Cases
✅ Configuration Management: Keep systems consistent

✅ CI/CD & App Deployment: Automate build & release

✅ Cloud Provisioning: Integrate with AWS, Azure, GCP

✅ Security Automation: Enforce access policies and firewall rules

✅ Network Configuration: Automate routers, switches, and firewalls

🔐 Security Practices
Uses SSH key-based authentication

Enforces Role-Based Access Control (RBAC)

Tracks changes for auditing and accountability

Leverages logging to monitor authorized changes and prevent misuse

⚖️ Pros and Cons
✅ Pros	❌ Cons
Agentless, uses SSH	Learning curve for YAML and modules
Simple syntax (YAML)	Less support for Windows
Easy to scale across Linux systems	Performance drops with 1000s of devices
Strong community (Ansible Galaxy)	Heavily depends on SSH
RBAC and secure automation	AAP requires paid subscription

✅ Conclusion
Ansible is a powerful and lightweight tool for automating repetitive IT tasks. Its agentless, push-based model is easy to adopt and fits naturally into hybrid and cloud-first environments. With strong community support, reusable roles, and robust security features, Ansible remains a top-tier choice for modern IT automation.
