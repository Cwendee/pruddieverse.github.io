---
title: "Multi-AZ Nginx Orchestration"
date: 2025-12-30
layout: "single"
summary: "A high-availability web architecture deployed on AWS using Ansible for automated configuration management."
github_link: "https://github.com/Cwendee/multi-az-nginx-orchestration"
---

A high-availability web architecture deployed on AWS using Ansible for automated configuration management. This project demonstrates the ability to design, provision, and orchestrate a distributed system that remains resilient and secure.

## 🏗️ Architecture
- **Infrastructure:** Custom AWS VPC across 2 Availability Zones (AZs).
- **Load Balancer:** 1 Ubuntu EC2 instance running Nginx as a Reverse Proxy.
- **Web Tier:** 2 Ubuntu EC2 instances serving unique content.
- **Automation:** Ansible playbooks for zero-touch deployment.

## 🛠️ Troubleshooting & Engineering Insights
### 1. The 504 Gateway Timeout
**Issue:** After initial configuration, the Load Balancer returned a 504 Gateway Timeout. 
**Fix:** Audited security group rules and target group health checks.

### 2. Ansible Connection Timeout
**Issue:** Terminal reported UNREACHABLE for the Load Balancer node.
**Fix:** Audited SSH keys and ensured inventory matched dynamic IPs.
