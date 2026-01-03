---
title: "Project 2: Multi-AZ Nginx Orchestration"
date: 2025-12-27
summary: "High-availability load balancing across AWS Availability Zones."
---

## Overview
This project demonstrates the deployment of a highly available Nginx web server environment. By utilizing multiple Availability Zones (AZs), the setup ensures that the application remains reachable even if one zone experiences an outage.

## Architecture

The setup includes an Application Load Balancer (ALB) distributing traffic to Nginx instances residing in different Private Subnets across two Availability Zones.

## Execution & Verification
The environment was provisioned using an Ansible Control Node. I verified the setup by intentionally stopping one instance and observing the Load Balancer redirecting traffic to the healthy node, ensuring zero downtime.

<a href="https://github.com/Cwendee/multi-az-nginx-orchestration" class="github-card">➡️ See Full Project</a>
