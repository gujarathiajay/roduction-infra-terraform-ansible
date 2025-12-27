# Production-Ready AWS Infrastructure using Terraform & Ansible

## Project Overview
This project demonstrates the design and deployment of a production-ready cloud infrastructure on AWS using Infrastructure as Code (IaC). Terraform is used to provision scalable and highly available AWS resources, while Ansible automates server configuration and application setup. The project eliminates manual infrastructure management and follows real-world DevOps best practices.

## Architecture Overview
- DevOps Control Server (Terraform & Ansible)
- AWS VPC with public subnets
- Web Tier EC2 instances
- Application Tier EC2 instances
- Security Groups and networking components
- Remote backend for Terraform state management

## Tools & Technologies Used
- AWS (EC2, VPC, Security Groups, S3, DynamoDB)
- Terraform (Infrastructure as Code)
- Ansible (Configuration Management)
- Git & GitHub
- Linux (Ubuntu)

## Deployment Steps
1. Create a DevOps control server on AWS.
2. Install Terraform, Ansible, AWS CLI, and Git.
3. Configure Terraform remote backend using S3 and DynamoDB.
4. Provision AWS infrastructure using Terraform.
5. Generate Ansible inventory from Terraform outputs.
6. Configure servers and deploy applications using Ansible.
7. Verify application availability and infrastructure health.

## Challenges Faced
- Managing Terraform remote state securely.
- Automating multi-tier configuration using Ansible.
- Ensuring idempotent and repeatable deployments.
- Handling SSH access and security group rules.

## Outcome
- Fully automated infrastructure provisioning.
- Scalable and production-ready AWS environment.
- Reduced manual errors using IaC and automation.
- Real-world DevOps workflow simulation.

## Author
Ajay Kumar Gujarathi
