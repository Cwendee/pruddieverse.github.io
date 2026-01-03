---
title: "Automated Multi-Node Infrastructure (Ansible + AWS)"
date: 2026-01-03
summary: "Automated the provisioning and configuration of a multi-node web infrastructure on AWS using Ansible."
---

<p style="color: #5a8ccf; font-size: 1.4rem; font-weight: 700; margin-bottom: 30px;">Automated Multi-Node Infrastructure (Ansible + AWS)</p>

<p style="margin-bottom: 5px;"><strong style="color: #9ca3af; font-size: 1.1rem;">Summary</strong></p>
<p style="margin-top: 0; color: #9ca3af;">Automated the provisioning and configuration of a multi-node web infrastructure on AWS using Ansible, transitioning from manual setup to fully orchestrated Infrastructure as Code.</p>

<p style="margin-bottom: 5px;"><strong style="color: #9ca3af; font-size: 1.1rem;">🎯 Problem & Objective</strong></p>
<p style="margin-top: 0; color: #9ca3af;">Manual server configuration does not scale and often leads to inconsistencies. This project demonstrates how configuration management can enforce consistency, idempotency, and scalability across multiple cloud servers.</p>

<p style="margin-bottom: 5px;"><strong style="color: #9ca3af; font-size: 1.1rem;">🧠 What I Built</strong></p>
<ul style="color: #9ca3af; margin-top: 0;">
  <li>Designed a 1-to-2 orchestration architecture where a single Ansible control node manages multiple EC2 instances</li>
  <li>Automated installation and configuration of Apache (httpd) and Git</li>
  <li>Deployed a professional Bootstrap-based portfolio theme directly from GitHub</li>
  <li>Implemented regex-driven content updates for precise, case-insensitive configuration changes</li>
  <li>Ensured idempotent playbook execution across all nodes</li>
</ul>

<p style="margin-bottom: 5px;"><strong style="color: #9ca3af; font-size: 1.1rem;">🛠 Tools & Technologies</strong></p>
<p style="margin-top: 0; color: #9ca3af;">Ansible · AWS EC2 · Apache (httpd) · Git · Linux</p>

<p style="margin-bottom: 5px;"><strong style="color: #9ca3af; font-size: 1.1rem;">✅ Execution & Verification</strong></p>
<ul style="color: #9ca3af; margin-top: 0;">
  <li>Validated successful orchestration through Ansible playbook execution results</li>
  <li>Confirmed live deployment by accessing the public DNS of managed EC2 instances</li>
</ul>

[➡️ View full project](https://github.com/Cwendee/ansible-web-orchestration-lab)
