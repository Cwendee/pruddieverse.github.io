---
title: "Automated Multi-Node Infrastructure"
date: 2025-12-27
summary: "Moving from manual configurations to automated orchestration with Ansible on AWS."
---

## Overview
This project focuses on automating the deployment of a multi-tier web application stack. By leveraging Ansible playbooks, I streamlined the configuration of web servers, database nodes, and load balancers, ensuring a repeatable and error-free environment.

## Architecture

The architecture consists of an Ansible Control Node managing multiple target hosts. The playbooks handle package installation, service configuration, and security hardening across the entire fleet.

## Execution & Verification
For a deep dive into the technical execution, including terminal logs showing the Ansible playbook runs and the final live service verification:

<a href="https://github.com/Cwendee/ansible-web-orchestration-lab" class="github-card">➡️ See Full Project</a>

The deployment was verified by running connectivity tests and ensuring the web application was accessible via the Load Balancer IP.
