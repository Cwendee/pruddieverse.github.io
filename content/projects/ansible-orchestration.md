---
title: "Automated Multi-Node Infrastructure (Ansible + AWS)"
date: 2025-01-03
summary: "Automated the provisioning and configuration of a multi-node web infrastructure on AWS using Ansible."
---

<h2 style="color: #5a8ccf; font-size: 1.4rem; margin-bottom: 30px;">Automated Multi-Node Infrastructure (Ansible + AWS)</h2>

<div style="margin-bottom: 25px;">
    <div style="color: #9ca3af; font-weight: 700; font-size: 1.1rem; margin-bottom: 5px;">Summary</div>
    <div style="color: #9ca3af;">Automated the provisioning and configuration of a multi-node web infrastructure on AWS using Ansible, transitioning from manual setup to fully orchestrated Infrastructure as Code.</div>
</div>

<div style="margin-bottom: 25px;">
    <div style="color: #9ca3af; font-weight: 700; font-size: 1.1rem; margin-bottom: 5px;">🎯 Problem & Objective</div>
    <div style="color: #9ca3af;">Manual server configuration does not scale and often leads to inconsistencies. This project demonstrates how configuration management can enforce consistency, idempotency, and scalability across multiple cloud servers.</div>
</div>

<div style="margin-bottom: 25px;">
    <div style="color: #9ca3af; font-weight: 700; font-size: 1.1rem; margin-bottom: 5px;">🧠 What I Built</div>
    <ul style="color: #9ca3af; margin-top: 5px;">
        <li>Designed a 1-to-2 orchestration architecture where a single Ansible control node manages multiple EC2 instances</li>
        <li>Automated installation and configuration of Apache (httpd) and Git</li>
        <li>Deployed a professional Bootstrap-based portfolio theme directly from GitHub</li>
        <li>Implemented regex-driven content updates for precise, case-insensitive configuration changes</li>
        <li>Ensured idempotent playbook execution across all nodes</li>
    </ul>
</div>

<div style="margin-bottom: 25px;">
    <div style="color: #9ca3af; font-weight: 700; font-size: 1.1rem; margin-bottom: 5px;">🛠 Tools & Technologies</div>
    <div style="color: #9ca3af;">Ansible · AWS EC2 · Apache (httpd) · Git · Linux</div>
</div>

<div style="margin-bottom: 25px;">
    <div style="color: #9ca3af; font-weight: 700; font-size: 1.1rem; margin-bottom: 5px;">✅ Execution & Verification</div>
    <ul style="color: #9ca3af; margin-top: 5px;">
        <li>Validated successful orchestration through Ansible playbook execution results</li>
        <li>Confirmed live deployment by accessing the public DNS of managed EC2 instances</li>
    </ul>
</div>

<div style="margin-bottom: 25px;">
    <div style="color: #9ca3af; font-weight: 700; font-size: 1.1rem; margin-bottom: 5px;">💡 Key Learnings</div>
    <ul style="color: #9ca3af; margin-top: 5px;">
        <li>Secure SSH key-based communication between cloud instances</li>
        <li>Practical use of regex in configuration automation</li>
        <li>Applying security best practices by protecting sensitive infrastructure details</li>
    </ul>
</div>

[➡️ View full project](https://github.com/Cwendee/ansible-web-orchestration-lab)
