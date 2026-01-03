---
title: "Automated Multi-Node Infrastructure (Ansible + AWS)"
date: 2025-01-03
summary: "Automated the provisioning and configuration of a multi-node web infrastructure on AWS using Ansible."
---

**Automated Multi-Node Infrastructure (Ansible + AWS)**

<h4>Summary</h4>
Automated the provisioning and configuration of a multi-node web infrastructure on AWS using Ansible, transitioning from manual setup to fully orchestrated Infrastructure as Code.

<h4>🎯 Problem & Objective</h4>
Manual server configuration does not scale and often leads to inconsistencies. This project demonstrates how configuration management can enforce consistency, idempotency, and scalability across multiple cloud servers.

<h4>🧠 What I Built</h4>
* Designed a 1-to-2 orchestration architecture where a single Ansible control node manages multiple EC2 instances
* Automated installation and configuration of Apache (httpd) and Git
* Deployed a professional Bootstrap-based portfolio theme directly from GitHub
* Implemented regex-driven content updates for precise, case-insensitive configuration changes
* Ensured idempotent playbook execution across all nodes

<h4>🛠 Tools & Technologies</h4>
Ansible · AWS EC2 · Apache (httpd) · Git · Linux

<h4>✅ Execution & Verification</h4>
* Validated successful orchestration through Ansible playbook execution results
* Confirmed live deployment by accessing the public DNS of managed EC2 instances

<h4>💡 Key Learnings</h4>
* Secure SSH key-based communication between cloud instances
* Practical use of regex in configuration automation
* Applying security best practices by protecting sensitive infrastructure details

[➡️ View full project](https://github.com/Cwendee/ansible-web-orchestration-lab)
