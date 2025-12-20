# AWS Web Application Deployment

## 📌 Project Overview
This project demonstrates the design and deployment of a secure multi-tier web application on AWS using managed services and cloud best practice

## 🛠️ Technologies Used
- Amazon EC2
- Amazon RDS (MySQL)
- Amazon S3
- Amazon DynamoDB
- Application Load Balancer
- Amazon Route 53
- NAT Gateway
- IAM
- Amazon VPC

## 🌐 Architecture Design
- Web servers deployed in **private subnets**
- NAT Gateway for secure outbound internet access
- A public ALB routes internet traffic to EC2 instances in private subnets, ensuring secure access and high availability.
- Route 53 for DNS and traffic routing
- RDS for structured data
- S3 for storing images
- DynamoDB for metadata

## 🔐 Security Implementation
- IAM roles with least-privilege access
- Private subnets for backend resources
- Security Groups and NACLs
- No public access to databases

## 📈 Performance & Optimization
- Achieved **99.9% uptime**
- Reduced latency to **<100ms** using ALB
- Optimized storage costs by **~25%**

## 📸 Implementation Screenshots

### VPC Design
![VPC](screenshots/VPC N-Virginia.png)

### EC2 & Load Balancer
![EC2](screenshots/03-ec2-alb.png)

### RDS Configuration
![RDS](screenshots/04-rds.png)

### Route 53
![Route53](screenshots/05-route53.png)

## 📄 Author
**Vishal Aramur**  
Cloud Engineer | AWS | DevOps  

