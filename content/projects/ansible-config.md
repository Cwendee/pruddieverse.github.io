---
title: "Project 1: Moving from Manual Configs to Automated Orchestration"
date: 2025-12-28
summary: "Milestone: Building a multi-node AWS infrastructure using Ansible to replace manual 'SSH-and-configure' steps with full Infrastructure as Code (IaC)."
---

I’m excited to share a milestone in my DevOps journey! I just completed a hands-on project building a multi-node web infrastructure on AWS, moving away from manual "SSH-and-configure" steps toward full Infrastructure as Code (IaC).

### 🚀 The Project
I used Ansible to orchestrate a cluster of RHEL-based (Amazon Linux 2) nodes. Instead of configuring servers one by one, I developed a playbook to: 

- ✅ **Provision and configure** Apache (httpd) across a fleet of instances. 
- ✅ **Deploy** a professional Bootstrap portfolio theme directly from GitHub. 
- ✅ **Surgical Updates:** Used Regex and the Ansible replace module to perform content updates (titles and avatars) across all nodes simultaneously.

### 🔍 View the Code
[**Direct Link to Ansible Repository**](https://github.com/Cwendee/ansible-config-mgt)

### 💡 The Real Learning
The highlight wasn't just when the code worked; it was the troubleshooting! I navigated Git merge conflicts, handled SSH key management, and practiced security best practices by using placeholders and .gitignore for sensitive data.

### 🎯 Key Takeaway
Automation is more than just speed—it’s about **idempotency** and ensuring that infrastructure is consistent, repeatable, and secure.
