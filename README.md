# AWS Self-Hosted VPN Infrastructure

## Overview
Deployed a production-grade self-hosted VPN on AWS EC2 using OpenVPN Access Server. This project demonstrates hands-on experience with cloud infrastructure, network security, IAM, monitoring, and system hardening.

## Technologies Used
- AWS EC2, OpenVPN Access Server
- AWS S3 (encrypted backups and logs)
- AWS IAM (roles and least-privilege access)
- AWS CloudWatch (monitoring and alerts)
- AWS Inspector (vulnerability scanning)
- AWS SNS (email notifications)
- UFW Firewall, SSH hardening

## What I Built
- Deployed OpenVPN on EC2 with public IP and security groups
- Configured IAM roles for admin, log viewer, and user access
- Set up S3 buckets with server-side encryption for backups and logs
- Built CloudWatch alarms for CPU usage and network traffic
- Ran AWS Inspector security scan and remediated findings
- Hardened SSH (disabled root login, disabled password auth)
- Configured UFW firewall rules

## Documentation
Full 24-page project documentation with screenshots included in this repo.
