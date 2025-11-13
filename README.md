# ⚙️ DevOps & Cloud Portfolio

![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=engabelal.devops-portfolio)

This is my **central portfolio** showcasing hands-on projects in **DevOps & Cloud Engineering**.
It highlights my work with **Infrastructure as Code (IaC)**, **automation**, **CI/CD pipelines**, and **container orchestration**.

---

## 📌 About Me

**Senior DevOps & Cloud Engineer** passionate about automation, scalability, and cloud-native solutions.

**Specialties:** AWS · Azure · Terraform · Ansible · Kubernetes · Docker · Linux · Virtualization · CI/CD Pipelines

### 💭 My Journey
> *From managing **enterprise data centers** to building **cloud platforms**—my journey has always been driven by a passion for **automation**. I constantly built **scripts and tools** to eliminate manual work and solve real problems. That's when I found **Cloud & DevOps**—where **infrastructure meets code**, and where I now build **automated, scalable systems** that just work.*

**🌐 Visit my website:** [cloudycode.dev](https://www.cloudycode.dev)

---

## 🧰 Tech Stack

<div align="center">

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Packer](https://img.shields.io/badge/Packer-02A8EF?style=for-the-badge&logo=packer&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 🗂️ Projects Overview

| # | Project | Tech Stack | Description |
|---|---------|------------|-------------|
| 1 | [ECS Fargate Blue/Green Deployment](https://github.com/engabelal/ecs-fargate-terraform-deployment) | Terraform · ECS Fargate · CodeDeploy · GitHub Actions | Production-ready Blue/Green deployment with automated CI/CD |
| 2 | [Terraform Layered Architecture](https://github.com/engabelal/terraform-layered-mern-rds) | Terraform · AWS · S3 Backend · RDS | Production-grade layered IaC with isolated state files |
| 3 | [Node.js CI/CD Pipeline](https://github.com/engabelal/simple-nodejs-ec2-cicd) | GitHub Actions · Terraform · AWS | Automated CI/CD with 13s updates |
| 4 | [Simple Web App - EC2 ASG](https://github.com/engabelal/simple-webapp-ec2-nlb-asg) | Terraform · AWS · NLB | Auto-scaling web infrastructure with multi-AZ |
| 5 | [Serverless Event Registration](https://github.com/engabelal/iac-aws-serverless-event) | Terraform · Lambda · DynamoDB | Serverless event management system |
| 6 | [Ansible AWS Dynamic Inventory](https://github.com/engabelal/ansible-aws-inventory-demo) | Ansible · AWS EC2 · SSH | Dynamic inventory with bastion host |
| 7 | [OpenText IAM - VMware](https://github.com/engabelal/iac-vmware-tf-vmprov) | Terraform · VMware | RHEL VM provisioning on vSphere |
| 8 | [MERN Stack - Ansible](https://github.com/engabelal/cm-ansible-mern-stack) | Ansible · YAML | Automated MERN stack deployment |
| 9 | [Packer Golden AMI](https://github.com/engabelal/packer-aws-devops-ami) | Packer · AWS · Ubuntu | Automated DevOps AMI creation |
| 10 | [ABCloudOps Scripts Kit](https://github.com/engabelal/abcloudops-scripts-kit) | Bash · AWS CLI | Cloud automation scripts toolkit |

---

## 📁 Projects Details

### ✅ [ECS Fargate Blue/Green Deployment with Terraform & GitHub Actions](https://github.com/engabelal/ecs-fargate-terraform-deployment)
- **Tech:** Terraform · AWS ECS Fargate · CodeDeploy · GitHub Actions · ALB · ECR · DynamoDB · Route53
- **Summary:** Production-ready containerized application deployment using AWS ECS Fargate with automated Blue/Green deployment strategy via CodeDeploy. Features modular Terraform architecture with 9 isolated modules, GitHub Actions CI/CD pipeline with OIDC authentication, automated Docker image builds and pushes to ECR, zero-downtime deployments with automatic rollback, and comprehensive automation scripts for setup, deployment, and cleanup. Includes URL shortener demo application with FastAPI backend.

📌 **Clone this project**
```bash
git clone https://github.com/engabelal/ecs-fargate-terraform-deployment.git
```
---
### ✅ [Terraform Layered Architecture - MERN Stack with RDS](https://github.com/engabelal/terraform-layered-mern-rds)
- **Tech:** Terraform · AWS VPC · RDS MariaDB · EC2 · S3 Backend · Remote State
- **Summary:** Production-grade layered Terraform architecture solving real-world infrastructure challenges. Splits infrastructure into 3 independent layers (Network → Database → App) with isolated S3 state files, remote state data sources, and automated deployment scripts. Eliminates state locking conflicts, reduces blast radius, and enables safe parallel team collaboration. Features versioned state files with object lock for disaster recovery.

📌 **Clone this project**
```bash
git clone https://github.com/engabelal/terraform-layered-mern-rds.git
```
---
### ✅ [Node.js CI/CD Pipeline to AWS EC2](https://github.com/engabelal/simple-nodejs-ec2-cicd)
- **Tech:** GitHub Actions · Terraform · AWS EC2 · S3 · IAM · Systems Manager · Node.js
- **Summary:** Production-ready CI/CD pipeline deploying Node.js applications to AWS EC2 with lightning-fast 13-second in-place updates. Features automated testing, artifact-based deployment, Infrastructure as Code with Terraform, and AWS Systems Manager for instant updates. Includes ABCloudOps Quote Generator demo app with professional UI.

📌 **Clone this project**
```bash
git clone https://github.com/engabelal/simple-nodejs-ec2-cicd.git
```
---
### ✅ [Simple Web App on AWS EC2 Auto Scaling with NLB](https://github.com/engabelal/simple-webapp-ec2-nlb-asg)
- **Tech:** Terraform · AWS EC2 · Auto Scaling · Network Load Balancer · VPC · NAT Gateway · Multi-AZ
- **Summary:** Production-ready AWS infrastructure with EC2 Auto Scaling Groups behind a Network Load Balancer. Features multi-AZ deployment, private subnets, NAT Gateway, and automated provisioning via Terraform. Supports dev/prod environments using tfvars files.

📌 **Clone this project**
```bash
git clone https://github.com/engabelal/simple-webapp-ec2-nlb-asg.git
```
---
### ✅ [Serverless Event Registration & Winner Selection – AWS](https://github.com/engabelal/iac-aws-serverless-event)
- **Tech:** Terraform · AWS Lambda · API Gateway · DynamoDB · S3 · CloudFront
- **Summary:** Infrastructure as Code project to provision a complete serverless application for event registration and winner selection. Includes API Gateway routes, Lambda functions, DynamoDB table, and static frontend hosted on S3 with CloudFront CDN.

📌 **Clone this project**
```bash
git clone https://github.com/engabelal/iac-aws-serverless-event.git
```
---
### ✅ [Ansible AWS Dynamic Inventory Demo](https://github.com/engabelal/ansible-aws-inventory-demo)
- **Tech:** Ansible · AWS EC2 · Dynamic Inventory · SSH ProxyCommand · Bastion Host
- **Summary:** Production-grade infrastructure automation using Ansible with AWS EC2 dynamic inventory. Demonstrates secure SSH tunneling through bastion hosts, tag-based server grouping, and zero-maintenance inventory management. Features optimized SSH connection multiplexing and comprehensive configuration examples.

📌 **Clone this project**
```bash
git clone https://github.com/engabelal/ansible-aws-inventory-demo.git
```
---
### ✅ [OpenText IAM & Patch Terraform Deployment - VMware](https://github.com/engabelal/iac-vmware-tf-vmprov)
- **Tech:** Terraform · Bash · VMware
- **Summary:** Terraform code for provisioning RHEL 9.4 VMs on VMware vSphere.Originally part of the OpenText IAM & Patch Management project.

📌 **Clone this project**
```bash
git clone https://github.com/engabelal/iac-vmware-tf-vmprov.git
```
---
### ✅ [Automated MERN Stack Deployment with Ansible ](https://github.com/engabelal/cm-ansible-mern-stack)
- **Tech:** Ansible · YAML · Bash
- **Summary:** Automated provisioning of a complete MERN stack (MongoDB, Express, React, Node.js) lab environment using modular Ansible roles.

📌 **Clone this project**
```bash
git clone https://github.com/engabelal/cm-ansible-mern-stack.git
```
---
### ✅ [Packer AWS DevOps Base AMI](https://github.com/engabelal/packer-aws-devops-ami)
- **Tech:** Packer · AWS EC2 · Ubuntu · Shell Scripting · Infrastructure as Code
- **Summary:** Automated Golden AMI creation using HashiCorp Packer. Builds production-ready Ubuntu 22.04 images with pre-installed DevOps tools (AWS CLI, Git, CloudWatch Agent, SSM Agent), security hardening (UFW, Fail2ban, SSH), and automatic updates. Reduces deployment time from 15 minutes to 60 seconds.

📌 **Clone this project**
```bash
git clone https://github.com/engabelal/packer-aws-devops-ami.git
```
---
### ✅ [ABCloudOps Scripts Kit](https://github.com/engabelal/abcloudops-scripts-kit)
- **Tech:** Bash · Shell Scripting · AWS CLI · Linux · Automation
- **Summary:** Production-ready DevOps automation scripts for cloud infrastructure management. Includes AWS cost optimization scanner, resource management tools, and system administration utilities. All scripts feature detailed documentation, color-coded output, and timestamped reports.

📌 **Clone this project**
```bash
git clone https://github.com/engabelal/abcloudops-scripts-kit.git
```
---

## 🔗 Quick Links

[🌐 Website](https://www.cloudycode.dev) | 
[📧 Email Me](mailto:eng.abelal@gmail.com) | 
[💼 LinkedIn](https://linkedin.com/in/engabelal) | 
[🐙 GitHub](https://github.com/engabelal)

---

## 📞 Contact
- **LinkedIn**: [linkedin.com/in/engabelal](https://linkedin.com/in/engabelal/)
- **Email**: eng.abelal@gmail.com
