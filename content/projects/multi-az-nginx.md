---
title: "Multi-AZ Nginx Orchestration"
date: 2025-12-29
layout: "single"
summary: "High-availability load balancing across AWS Availability Zones."
github_link: "https://github.com/Cwendee/multi-az-nginx-orchestration"
---

This project showcases the transition from manual server management to a highly available, automated infrastructure. By using **Nginx** as a load balancer and **Ansible** for orchestration, I deployed a resilient web environment across multiple AWS Availability Zones.

## 🏗️ System Architecture
This project demonstrates a high-availability Nginx orchestration across multiple AWS Availability Zones.

![Multi-AZ Architecture](/images/load-balancer-architecture.png)

## 🎯 Project Goals
* **High Availability:** Distribute traffic across two different AWS data centers (AZs).
* **Automated Scaling:** Prepare for horizontal scaling by using Ansible Playbooks.
* **Security:** Implement Security Groups and SSH key management via automation.

## 🛠 Tech Stack
* **Proxy/Load Balancer:** Nginx
* **Configuration Management:** Ansible
* **Infrastructure:** AWS EC2 (Multi-AZ)
* **Web Server:** Apache (Target Nodes)

## 🚀 Execution & Verification
The environment was provisioned using an Ansible Control Node. I verified the setup by intentionally stopping one instance and observing the Load Balancer redirecting traffic to the healthy node, ensuring zero downtime.

## 💡 Key Learning Moments
1. **Health Check Logic:** Understanding how Nginx determines if a backend node is "Up."
2. **Inventory Management:** Using Ansible host groups to target specific AZs.
3. **AWS Networking:** Deepening knowledge of VPCs, Subnets, and Public IPs.
