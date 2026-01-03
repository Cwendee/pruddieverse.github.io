---
title: "Automated Multi-Node Infrastructure (Ansible + AWS)"
date: 2025-01-03
summary: "Automated the provisioning and configuration of a multi-node web infrastructure on AWS using Ansible."
---

**Automated Multi-Node Infrastructure (Ansible + AWS)**

**Summary**

Automated the provisioning and configuration of a multi-node web infrastructure on AWS using Ansible, transitioning from manual setup to fully orchestrated Infrastructure as Code.

**🎯 Problem & Objective**

Single-zone deployments introduce availability risks and manual configurations do not scale. This project demonstrates how automation and orchestration can deliver high availability, consistency, and reliability across distributed cloud infrastructure.

**🧠 What I Built**
* Designed a 1-to-2 orchestration architecture where a single Ansible control node manages multiple EC2 instances
* Automated installation and configuration of Apache (httpd) and Git
* Deployed a professional Bootstrap-based portfolio theme directly from GitHub
* Implemented regex-driven content updates for precise, case-insensitive configuration changes
* Ensured idempotent playbook execution across all nodes

**🛠 Tools & Technologies**
Ansible · AWS EC2 · Apache (httpd) · Git · Linux

**✅ Execution & Verification**
* Validated successful orchestration through Ansible playbook execution results
* Confirmed live deployment by accessing the public DNS of managed EC2 instances

**💡 Key Learnings**
* Secure SSH key-based communication between cloud instances
* Practical use of regex in configuration automation
* Applying security best practices by protecting sensitive infrastructure details

<a href="https://github.com/Cwendee/ansible-web-orchestration-lab" target="_blank" style="display: inline-block; margin: 30px 0; padding: 12px 25px; background: #1e233c; border: 1px solid #2d3748; border-radius: 8px; text-decoration: none; color: #E6BE8A !important; font-weight: 700;">➡️ View full project</a>
