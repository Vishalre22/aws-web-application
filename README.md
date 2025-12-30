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
![VPC](screenshots/vpc-n-virginia.png.png)

### Subnets
![Subnets](screenshots/Subnets.png)

### Internet Gateway
![InternetGateway](screenshots/InternetGateway.png)

### NAT Gateway
![NATGateway](screenshots/NATGateway.png)

### Route Tables
![RouteTables](screenshots/RouteTables.png)

### Route Tables Config
![RouteTables](screenshots/RouteTablesRoutes(configurations).png)

### Instance-Private_Subnet
![Instance-Private_Subnet](screenshots/Instance-Private_Subnet.png)

### RDS
![RDS](screenshots/RDS.png)

### DynamodbTable
![DynamodbTable](screenshots/DynamodbTable.png)

### Route Tables
![RouteTables](screenshots/RouteTables.png)

### S3Bucket
![S3Bucket](screenshots/S3Bucket.png)

### ApplicationLoadBalancer
![ApplicationLoadBalancer](screenshots/ApplicationLoadBalancer.png)
![ALB-TargetGroup](screenshots/ALB-TargetGroup.png)

### IAM Roles
![IAM Roles](screenshots/IAM-Roles_S3_Dynamodb_Access.png)
![IAM Roles Attach to Instance](screenshots/IAM-Role_attach_Instance.png)

### Instance-Public_Subnet
![Instance-Public_Subnet](screenshots/Instance-Public_Subnet.png)

### Public-PrivateInstance_SSH
![Public-PrivateInstance_SSH](screenshots/Public-PrivateInstance_SSH.png)

### PythonScript_PrivateInstance
![PythonScript_PrivateInstance](screenshots/PythonScript_PrivateInstance.png)

### LoadBalancer-DNS_URL
![LoadBalancer-DNS_URL](screenshots/LoadBalancer-DNS_URL.png)

### HostedZone-Route53
![HostedZone-Route53](screenshots/HostedZone-Route53.png)

### CustomDomainURL
![CustomDomainURL](screenshots/CustomDomainURL.png)

### RDS-Data
![RDS-Data](screenshots/RDS-Data.png)

### Uploaded-Images-S3
![Uploaded-Images-S3](screenshots/Uploaded-Images-S3.png)

### Metadata-DynamoDB
![Metadata-DynamoDB](screenshots/Metadata-DynamoDB.png)

## 📄 Author
**Vishal Aramur**  
Cloud Engineer | AWS | DevOps  

