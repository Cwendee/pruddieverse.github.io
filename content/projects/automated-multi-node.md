---
title: "Automated Multi-Node Infrastructure"
date: 2025-12-28
layout: "single"
summary: "Moving from manual configurations to automated orchestration with Ansible on AWS."
github_link: "https://github.com/Cwendee/ansible-web-orchestration-lab"
---

This repository documents a hands-on project in **Infrastructure as Code (IaC)**. I built a multi-node environment where a single Ansible Master node orchestrates the deployment and deep customization of professional web servers across an AWS EC2 cluster.

## 🏗️ System Architecture
![Architecture](/images/architecture.png)

## 🚀 Execution & Verification
![Terminal](/images/terminal.png)

### Live Service Verification
![Webpage](/images/webpage.png)

## 🎯 Project Goals
* **Automate** the installation of Apache (httpd) and Git.
* **Deploy** a professional Bootstrap portfolio theme from GitHub.
* **Orchestrate** surgical content changes using Ansible and Regex.
* **Ensure Idempotency** across the entire infrastructure.

## 🛠 Tech Stack
* **Configuration Management:** Ansible
* **Infrastructure:** AWS EC2
* **Web Server:** Apache (httpd)
* **Version Control:** Git

## 🚀 Execution & Verification
The following terminal output demonstrates the Ansible playbook running across the inventory. Notice the "changed" status, indicating the successful application of the desired state.

![Ansible Playbook Execution](/images/ansible-playbook-execution.png)

### Live Service Verification
Once the orchestration was complete, I verified the deployment by accessing the public DNS of the managed nodes. The customized portfolio was live and functioning as expected.

![Web Page Verification](/images/nginx-node-verification.png)

## 💡 Key Learning Moments
1. **SSH Key Management:** Secure communication between cloud instances.
2. **Regex Implementation:** Handle case-insensitive text replacement.
3. **Security Best Practices:** Redacted sensitive IP addresses.
