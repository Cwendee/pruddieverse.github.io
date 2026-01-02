---
title: "Multi-AZ Nginx Orchestration"
date: 2025-12-29
layout: "single"
summary: "High-availability load balancing across AWS Availability Zones."
github_link: "https://github.com/Cwendee/multi-az-nginx-orchestration"
---

## 🏗️ System Architecture
This project demonstrates a high-availability Nginx orchestration across multiple AWS Availability Zones to ensure zero downtime and efficient traffic distribution.

![Multi-AZ Load Balancer Architecture](/images/load-balancer-architecture.png)

## 🎯 Project Highlights
* **High Availability:** Traffic is distributed across multiple AZs.
* **Health Checks:** Automated monitoring to ensure traffic only hits healthy nodes.
* **Ansible Automated:** Every component from Nginx config to firewall rules is managed via code.

## 🛠 Tech Stack
* **Proxy/Load Balancer:** Nginx
* **Infrastructure:** AWS EC2
* **Automation:** Ansible
