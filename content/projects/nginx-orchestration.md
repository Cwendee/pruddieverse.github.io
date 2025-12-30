---
title: "Multi-AZ Nginx Orchestration"
date: 2025-12-30
summary: "A high-availability web architecture deployed on AWS using Ansible for automated configuration management."
---

🏗️ Architecture
Infrastructure: Custom AWS VPC across 2 Availability Zones (AZs) for fault tolerance.
Load Balancer: 1 Ubuntu EC2 instance running Nginx as a Reverse Proxy.
Web Tier: 2 Ubuntu EC2 instances serving unique content to verify load distribution.
Automation: Ansible playbooks for zero-touch deployment and configuration.

🚀 Key Features
* High Availability: Distributed nodes across multiple AZs.
* Security: Layered Security Groups.
* Idempotent Automation: Ansible logic ensures state consistency.

🛠️ Tech Stack
* Cloud: AWS (EC2, VPC)
* Configuration Management: Ansible
* Web Server: Nginx

[**View Source Code on GitHub**](https://github.com/Cwendee/multi-az-nginx-orchestration)
