---
title: "Automated Multi-Node Infrastructure"
date: 2025-12-28
layout: "single"
summary: "Moving from manual configurations to automated orchestration with Ansible on AWS."
github_link: "https://github.com/Cwendee/ansible-web-orchestration-lab"
---

This repository documents a hands-on project in **Infrastructure as Code (IaC)**. I built a multi-node environment where a single Ansible Master node orchestrates the deployment and deep customization of professional web servers across an AWS EC2 cluster.

## 🏗️ System Architecture
To demonstrate scalability, I designed a 1-to-2 orchestration flow. This ensures that configurations remain consistent across a fleet of servers simultaneously.

![Architecture](/images/ansible-lab-architecture.png)

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
For a deep dive into the technical execution, including terminal logs showing the Ansible playbook runs and the final live service verification, please visit the [GitHub Repository](https://github.com/Cwendee/ansible-web-orchestration-lab).

## 💡 Key Learning Moments
1. **SSH Key Management:** Secure communication between cloud instances.
2. **Regex Implementation:** Handle case-insensitive text replacement.
3. **Security Best Practices:** Redacted sensitive IP addresses.
