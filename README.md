# 🌐 Ansible Apache Deployment on AWS EC2

This mini-project uses **Ansible** to automate the deployment of an **Apache web server** on a **Ubuntu EC2 instance**. The controller node runs from a **WSL (Windows Subsystem for Linux)** environment on a local machine.

---

## 🚀 Project Objectives

- Install and configure **Apache2** web server
- Deploy a custom `index.html` landing page
- Allow HTTP traffic using **UFW** firewall (Ubuntu)
- Demonstrate basic use of **Infrastructure as Code (IaC)** with Ansible

---

## 🖥️ Infrastructure Overview

- **Control Node**: Ubuntu via WSL on Windows
- **Managed Node**: 1x Ubuntu EC2 instance
- **Communication**: SSH using PEM key

---

## 📁 Project Structure

```bash
ansible-apache-deploy/
├── apache_deploy.yml        # Ansible playbook for Apache deployment
├── index.html               # Custom HTML landing page
├── inventory.ini            # Ansible inventory file (EC2 instance IPs)
└── README.md   
