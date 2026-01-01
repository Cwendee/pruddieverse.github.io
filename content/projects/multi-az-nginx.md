---
title: "Multi-AZ Nginx Orchestration"
date: 2025-12-30
layout: "single"
summary: "A high-availability web architecture deployed on AWS using Ansible for automated configuration management."
github_link: "https://github.com/Cwendee/multi-az-nginx-orchestration"
---

This project demonstrates the design and deployment of a resilient, high-availability web architecture. By distributing workloads across multiple AWS Availability Zones, the system ensures uptime and performance even during localized failures.

## 🏗️ System Architecture
The design utilizes an Nginx Load Balancer to distribute traffic between two backend web servers located in separate subnets.

![Load Balancer Architecture](/images/load-balancer-architecture.png)

## 🎯 Key Features
* **High Availability:** Infrastructure spans 2 Availability Zones (AZs) to prevent a single point of failure.
* **Reverse Proxy:** Nginx is configured to handle client requests and intelligently route traffic.
* **Automated Provisioning:** Ansible playbooks handle the complete setup of Nginx and backend configurations.

## 🛠️ Troubleshooting & Engineering Insights

### 1. The 504 Gateway Timeout
**Challenge:** After initial configuration, the Load Balancer returned a 504 Gateway Timeout error.
**Resolution:** Performed a connectivity audit. Discovered that the backend security groups were not allowing traffic from the Load Balancer's private IP. Updated the inbound rules to permit port 80 traffic only from the Load Balancer, enhancing security.

### 2. Ansible Connection Timeout
**Challenge:** Terminal reported `UNREACHABLE` for the Load Balancer node during a playbook run.
**Resolution:** Audited SSH key paths and confirmed that the inventory file was using the correct Elastic IP. Implemented `ssh-agent` forwarding to streamline future connections.

## 🛠 Tech Stack
* **Proxy/LB:** Nginx
* **Infrastructure:** AWS EC2 (Ubuntu)
* **Automation:** Ansible
* **Networking:** VPC, Subnets, Security Groups