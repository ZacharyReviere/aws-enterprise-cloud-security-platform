![AWS](https://img.shields.io/badge/AWS-Cloud-orange?style=for-the-badge&logo=amazonaws)
![Terraform](https://img.shields.io/badge/Terraform-IaC-623CE4?style=for-the-badge&logo=terraform)
![Git](https://img.shields.io/badge/Git-Version_Control-F05032?style=for-the-badge&logo=git)
![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)
![CloudWatch](https://img.shields.io/badge/Amazon-CloudWatch-FF4F8B?style=for-the-badge&logo=amazoncloudwatch)


# AWS Enterprise Cloud Security Platform

## Overview

This project demonstrates how to deploy and manage secure AWS infrastructure using Infrastructure as Code (Terraform). The environment was built in a personal AWS account and follows security best practices including S3 encryption, versioning, and public access blocking.

## Project Goals

- Build secure AWS infrastructure
- Learn Infrastructure as Code (Terraform)
- Implement AWS security best practices
- Version control infrastructure with Git and GitHub

## Technologies Used

- AWS
- Terraform
- Git
- GitHub
- Amazon S3
- IAM
- CloudShell

## 📸 AWS Resources

These screenshots show the AWS resources deployed and configured as part of this cloud security lab.

### Amazon EC2 Instance
![EC2 Instance](./ec2.png)

- Amazon Linux 2023 EC2 instance
- CloudWatch Agent installed
- Running in the AWS Free Tier

### Amazon S3 Buckets
![Amazon S3](./s3.png)

- CloudTrail log storage
- Terraform state storage
- Versioning and encryption enabled
- Public access blocked

### CloudWatch Monitoring
![CloudWatch](./CloudWatch.png)

- CloudWatch metrics
- CPU monitoring
- CloudWatch alarms
- Performance visibility

### IAM Roles
![IAM Roles](./IAM-Role.png)

- Least privilege access
- EC2 IAM role
- CloudWatch Agent role
- Service-linked roles

## Security Features

- S3 Server-Side Encryption (AES-256)
- S3 Versioning
- S3 Public Access Block
- Infrastructure managed with Terraform
- Version controlled with GitHub

## Project Structure

```text
terraform/
├── main.tf
├── variables.tf
└── outputs.tf
```

## Skills Demonstrated

- AWS Cloud Security
- Infrastructure as Code (IaC)
- Terraform
- Cloud Infrastructure Deployment
- Git Version Control
- Secure AWS Configuration

## Future Improvements

- VPC
- EC2
- CloudWatch
- IAM Roles
- Security Groups
- VPC Flow Logs
- AWS Config
- GuardDuty
- Security Hub

## Author

**Zachary Reviere**

Computer Science | Cloud Security | AWS | Terraform
