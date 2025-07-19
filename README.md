# 🚀 E-Commerce Website Deployment on AWS

A comprehensive cloud project demonstrating **multi-platform deployment of an e-commerce website** using **AWS services** including EC2 (Ubuntu & Windows), S3 Bucket, and Elastic Beanstalk.

---

## 📖 Description

This project showcases the **end-to-end process** of deploying an e-commerce website on **Amazon Web Services** using a variety of compute and storage services. It is built to demonstrate flexibility, scalability, and real-world cloud deployment techniques using **multiple AMIs**, **custom networking**, **VPCs**, and **version-controlled S3 hosting**.

---

## 🛠 Technologies Used

- **Amazon EC2** (Ubuntu & Windows AMIs)
- **Amazon S3** with versioning
- **AWS Elastic Beanstalk**
- **Amazon VPC**
- **Security Groups & Elastic IP**
- **MobaXterm** (SSH and RDP for remote management)
- **Apache & IIS web servers**
- **Basic Linux Shell**

---

## ✅ Features

- Deployment of an e-commerce website using:
  - EC2 (Ubuntu) with Apache Web Server
  - EC2 (Windows) with IIS Web Server
  - Elastic Beanstalk (automated orchestration)
  - S3 Bucket (static website hosting)
- Custom **VPC setup** with public subnets, internet gateways, and route tables.
- Static IP allocation using **Elastic IPs**
- **File versioning** enabled in S3 for recovery
- Seamless integration with AWS networking and security features
- Accessible via public IPs and Elastic Beanstalk-provided endpoints

---

## 🧩 How to Use

### 🔧 Prerequisites
- AWS Account
- AWS IAM access (with EC2, VPC, S3, Elastic Beanstalk permissions)
- MobaXterm installed for connecting via SSH/RDP
- Basic knowledge of Linux commands

### 🪜 Setup Steps
1. Clone this repository.
2. Choose the deployment method:
   - **Ubuntu EC2**: Configure VPC ➝ Launch EC2 ➝ Install Apache ➝ Upload Files ➝ Access via IP
   - **Windows EC2**: Configure VPC ➝ Launch Windows EC2 ➝ Install IIS ➝ Upload Files ➝ Access via IP
   - **Elastic Beanstalk**: Package code ➝ Create Environment ➝ Upload ➝ Get Public URL
   - **S3 Bucket**: Create bucket ➝ Upload files ➝ Enable static hosting ➝ Access via endpoint
3. Configure security groups and ensure ports 80 (HTTP), 443 (HTTPS), and 22/3389 (SSH/RDP) are open.
4. Access your deployed website from a browser.

---

## 👥 Credits

### 👩‍💻 Project Lead:
**Sanjana Singineedi**  
[GitHub Profile](https://github.com/sanjanasingineedi)  
Email: sanjanasingineedi0508@gmail.com
### Team Members:
**Eswar Kumar**,
**Sai Ram**

### 🧑‍🤝‍🧑 Internship Support:
- **T-Hub, Aditya Educational Institutions**
  - Website: [https://technicalhub.io](https://technicalhub.io)
  - Role: Internship & Cloud Skill Training Provider

---

## 💡 Challenges Faced

- Initial EC2 misconfiguration (security groups, networking)
- Understanding S3 versioning impact on cost
- Integrating Elastic Beanstalk with custom VPC
- Handling IAM roles and RDP credential decryption
- Overcoming deployment issues in Windows environment

---

## 🏆 Highlights

- Successfully deployed the same e-commerce website on **four different AWS platforms**
- Implemented **manual and automated deployment pipelines**
- Learned real-world **cloud architecture**
- Gained practical experience in **networking, security, scaling, and troubleshooting**

---

## 📚 What I Learned

- Hands-on deployment using **IaaS and PaaS**
- Working with **custom subnets, routing, and gateways**
- Building production-like environments in AWS
- Secure and scalable web hosting approaches
- Cloud-native version control with **S3 versioning**

---

## 🚀 What’s Next

- Automate EC2 deployments using Terraform or AWS CloudFormation
- Add CI/CD using GitHub Actions and CodeDeploy
- Implement HTTPS using AWS Certificate Manager
- Add monitoring and alerts via CloudWatch

---
