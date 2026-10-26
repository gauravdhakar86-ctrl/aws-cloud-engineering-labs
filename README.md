# AWS Cloud Engineering Labs

A hands-on learning portfolio documenting AWS cloud labs, Linux administration, cloud networking, security, monitoring, and infrastructure automation.

> **Progress note:** Only labs that have actually been completed are marked **Completed**. Other folders are learning roadmap items and should be updated after performing each lab.

## Completed Lab

| Lab | Status | Topics |
|---|---|---|
| [01 — EC2 Apache Web Hosting](01-ec2-apache-web-hosting/README.md) | Completed | EC2, Linux, SSH, Apache HTTP Server, HTML, HTTP verification |

## Learning Roadmap

- [ ] EC2, AMIs, Launch Templates, Auto Scaling
- [ ] S3, EBS, EFS, snapshots
- [ ] VPC, subnets, route tables, Internet Gateway, NAT Gateway
- [ ] Security Groups, NACLs, VPC endpoints
- [ ] Application Load Balancer, Network Load Balancer, Target Groups
- [ ] IAM users, roles, policies
- [ ] CloudWatch, CloudTrail, alarms
- [ ] RDS, DynamoDB
- [ ] Lambda, API Gateway, EventBridge
- [ ] ECR, ECS, EKS
- [ ] CloudFormation, Terraform
- [ ] Route 53, CloudFront
- [ ] SQS, SNS
- [ ] Projects: highly available web application, CloudBridge hybrid-cloud architecture

## Repository Structure

Each completed lab should include:
- `README.md` — goal, prerequisites, steps, verification, result, and cleanup
- `screenshots/` — screenshots from the actual lab
- `scripts/` — only when scripts are useful and safe to share

## Security and Cost Reminders

- Never commit private keys (`.pem`), passwords, AWS access keys, session tokens, or account secrets.
- Restrict SSH (port 22) to your own IP address whenever possible.
- Public HTTP/HTTPS access should be opened only when required for the lab.
- Stop or terminate resources when finished. NAT Gateways, load balancers, public IPv4 addresses, and some other resources can incur charges.
- Screenshots may show public IP addresses or account details; review them before publishing.

## About

Beginner-level hands-on practice for AWS Cloud Engineering. This repository is a work in progress; roadmap items are not claims of completed experience.
