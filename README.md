# AWS 3-Tier Architecture Deployment

## Project Overview

This project demonstrates the deployment of a traditional 3-tier web application architecture on AWS using core cloud services.

The architecture consists of:

- Presentation Layer (Amazon S3)
- Application Layer (Amazon EC2)
- Database Layer (Amazon RDS)

The objective of this project is to build a secure, scalable, and highly available infrastructure while following AWS best practices.

---

## Architecture

Frontend (S3 Static Website)
        │
        ▼
Backend Application (EC2)
        │
        ▼
Database (RDS MySQL)

---

## AWS Services Used

| Service | Purpose |
|----------|----------|
| Amazon S3 | Static Website Hosting |
| Amazon EC2 | Application Server |
| Amazon RDS | Database Layer |
| Amazon VPC | Network Isolation |
| IAM | Access Management |
| Route 53 | DNS Management |
| Security Groups | Traffic Control |

---

## Project Workflow

1. User accesses the website hosted on Amazon S3.
2. Frontend sends requests to the EC2 application server.
3. EC2 processes user requests.
4. Data is stored in Amazon RDS.
5. Route 53 provides custom domain access.

---

## Deployment Steps

### Step 1: Create VPC

- Create Public Subnet
- Create Private Subnet
- Configure Internet Gateway
- Configure Route Tables

### Step 2: Deploy Frontend

- Create S3 Bucket
- Enable Static Website Hosting
- Upload HTML/CSS/JS files

### Step 3: Deploy Backend

- Launch EC2 Instance
- Install Web Server
- Deploy Application

### Step 4: Configure Database

- Create Amazon RDS Instance
- Configure Security Groups
- Connect EC2 with RDS

### Step 5: Configure Route 53

- Register Domain
- Create DNS Records

---

## Security Implementation

- IAM Roles
- Security Groups
- Private Database Subnet
- Least Privilege Access

---

## Expected Outcome

- Fully Functional 3-Tier Application
- Secure AWS Infrastructure
- Custom Domain Access
- Scalable Architecture

---

## Author

**Shudhanshu Dwivedi**

DevOps & Cloud Enthusiast

STAR AGILE Internship Project
