# AWS-refactoring-vprofile
A comprehensive AWS cloud migration project demonstrating **re-architecture/refactoring** strategy by migrating a traditional multi-tier web application (VProfile) from infrastructure-based deployment to AWS managed services (PaaS/SaaS). This project showcases modern cloud-native architecture, DevOps best practices, and infrastructure automation.

### **Migration Strategy**: Refactoring (Re-architecture)
**Goal**: Transform traditional infrastructure workloads into cloud-native AWS managed services for improved agility, scalability, and reduced operational overhead.

## 🏗️ Architecture Overview

### **Before (Traditional Infrastructure)**
- Application servers on VMs/EC2
- Manual load balancer configuration
- Self-managed MySQL database
- Memcached on EC2
- RabbitMQ on EC2
- High operational overhead

### **After (AWS Managed Services)**
- **AWS Elastic Beanstalk** - PaaS for application deployment
- **Amazon RDS** - Managed MySQL database
- **Amazon ElastiCache** - Managed Memcached caching
- **Amazon MQ** - Managed RabbitMQ message broker
- **Amazon CloudFront** - CDN for global content delivery
- **Amazon Route 53** - DNS management
- **Application Load Balancer** - Automatic traffic distribution
- **Auto Scaling Groups** - Dynamic capacity management

### Architecture Diagram
![c3c1e0a3-3d5c-4584-8755-80f7f5ad7573](https://github.com/user-attachments/assets/7f5cc1c0-830e-4490-904b-a685659893ad)


## 🛠️ Technologies Used

| Category | Technology | Purpose |
|----------|-----------|---------|
| **Cloud Platform** | AWS | Infrastructure provider |
| **Compute** | Elastic Beanstalk, EC2 | Application hosting |
| **Database** | Amazon RDS (MySQL) | Relational data storage |
| **Caching** | Amazon ElastiCache | Performance optimization |
| **Messaging** | Amazon MQ (RabbitMQ) | Asynchronous communication |
| **CDN** | Amazon CloudFront | Global content delivery |
| **DNS** | Amazon Route 53 | Domain management |
| **Load Balancer** | Application Load Balancer | Traffic distribution |
| **Monitoring** | Amazon CloudWatch | Metrics and logging |
| **Storage** | Amazon S3 | Artifact storage |
| **IaC** | Terraform, CloudFormation | Infrastructure automation |
| **CI/CD** | GitHub Actions | Automated deployment |
| **Security** | Security Groups, IAM | Access control |


## ✨ Key Features

- ✅ **Zero Infrastructure Management** - Fully managed AWS services
- ✅ **High Availability** - Multi-AZ deployments with automatic failover
- ✅ **Auto Scaling** - Dynamic capacity based on demand
- ✅ **Global Performance** - CloudFront edge caching (400+ locations)
- ✅ **Security First** - VPC isolation, security groups, encryption
- ✅ **Cost Optimized** - Pay-as-you-go with reserved instances
- ✅ **Self-Healing** - Automated health checks and recovery
- ✅ **Infrastructure as Code** - Terraform templates included
- ✅ **CI/CD Pipeline** - Automated build and deployment
- ✅ **Monitoring & Alerts** - CloudWatch dashboards and alarms

## 📦 Prerequisites

### **Required**
- AWS Account with appropriate IAM permissions
- AWS CLI installed and configured
- Git installed
- Maven 3.6+ or Gradle 7+ (for building artifacts)
- Java 11+ JDK
- Basic understanding of AWS services

