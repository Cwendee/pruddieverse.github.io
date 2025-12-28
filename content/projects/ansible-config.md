---
title: "Automated Multi-Node Infrastructure"
date: 2025-12-28
summary: "Moving from manual configurations to automated orchestration with Ansible on AWS."
---

### Project Overview

I moved away from manual "SSH-and-configure" steps toward full Infrastructure as Code (IaC). This project focuses on the deployment of a multi-node cluster on AWS.

### Technical Stack

* **Orchestration:** Ansible
* **Infrastructure:** AWS EC2 (RHEL)
* **Deployment:** Git & GitHub

### Key Implementation

* **Fleet Provisioning:** Automated Apache configuration across multiple nodes simultaneously.
* **Surgical Updates:** Used Regex and the Ansible replace module for content updates across the cluster.
* **Security:** Managed SSH key authentication and secure environment data protocols.

### Engineering Takeaway

Automation is more than just speed—it’s about ensuring that infrastructure is consistent, repeatable, and secure.

[**View Source Code on GitHub**](https://github.com/Cwendee/ansible-config-mgt)
