---
title: "Automated Multi-Node Infrastructure (Ansible + AWS)"
date: 2025-01-03
summary: "Automated the provisioning and configuration of a multi-node web infrastructure on AWS using Ansible."
---

**Automated Multi-Node Infrastructure (Ansible + AWS)**

<div class="project-content">

<span class="sub-heading">Summary</span>
Automated the provisioning and configuration of a multi-node web infrastructure on AWS using Ansible, transitioning from manual setup to fully orchestrated Infrastructure as Code.

<span class="sub-heading">🎯 Problem & Objective</span>
Manual server configuration does not scale and often leads to inconsistencies. This project demonstrates how configuration management can enforce consistency, idempotency, and scalability across multiple cloud servers.

<span class="sub-heading">🧠 What I Built</span>
* Designed a 1-to-2 orchestration architecture where a single Ansible control node manages multiple EC2 instances
* Automated installation and configuration of Apache (httpd) and Git
* Deployed a professional Bootstrap-based portfolio theme directly from GitHub
* Implemented regex-driven content updates for precise, case-insensitive configuration changes
* Ensured idempotent playbook execution across all nodes

<span class="sub-heading">🛠 Tools & Technologies</span>
Ansible · AWS EC2 · Apache (httpd) · Git · Linux

<span class="sub-heading">✅ Execution & Verification</span>
* Validated successful orchestration through Ansible playbook execution results
* Confirmed live deployment by accessing the public DNS of managed EC2 instances

<span class="sub-heading">💡 Key Learnings</span>
* Secure SSH key-based communication between cloud instances
* Practical use of regex in configuration automation
* Applying security best practices by protecting sensitive infrastructure details

</div>

[➡️ View full project](https://github.com/Cwendee/ansible-web-orchestration-lab)
