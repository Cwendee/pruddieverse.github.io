---
title: "Automated Multi-Node Infrastructure Orchestration"
date: 2025-12-28
summary: "Architected and deployed a scalable web infrastructure on AWS using Ansible to replace manual configuration with Infrastructure as Code (IaC)."
---

### Project Overview
Transitioned infrastructure management from manual SSH-based configurations to a fully automated orchestration model. This project focuses on the deployment and synchronization of a multi-node RHEL-based environment on AWS.

### Technical Specifications
- **Orchestration:** Ansible (Idempotent Playbooks)
- **Infrastructure:** AWS EC2 (RHEL/Amazon Linux 2)
- **Web Stack:** Apache (httpd), PHP
- **Source Control:** Git/GitHub

### Key Deliverables & Implementation
- **Fleet Provisioning:** Automated the configuration of Apache (httpd) across multiple distributed nodes simultaneously.
- **Automated Deployment:** Established a pipeline to pull and deploy Bootstrap-based frontend assets directly from GitHub repositories.
- **Global Configuration Management:** Implemented the Ansible  module with Regex patterns to execute surgical content updates across the entire server cluster in a single execution.
- **Security & Integrity:** Managed SSH key authentication and utilized  protocols to ensure sensitive environment data remained secure during the CI/CD process.

### Engineering Takeaway
The implementation demonstrated the power of **idempotency** in configuration management—ensuring consistent, repeatable system states across heterogeneous environments while significantly reducing deployment lead times.

---

### 🔗 Repository Access
[**View Technical Source Code on GitHub**](https://github.com/Cwendee/ansible-config-mgt)
