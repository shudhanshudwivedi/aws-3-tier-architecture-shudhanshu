# AWS 3-Tier Architecture Deployment Guide

## Objective

Deploy a secure and scalable 3-tier application architecture on AWS using:

- Amazon S3
- Amazon EC2
- Amazon RDS
- Amazon VPC
- IAM
- Route 53

---

## Step 1: Create VPC

1. Create a new VPC
2. Create Public Subnet
3. Create Private Subnet
4. Attach Internet Gateway
5. Configure Route Tables

---

## Step 2: Configure Security Groups

### EC2 Security Group

Allow:

- HTTP (80)
- HTTPS (443)
- SSH (22)

### RDS Security Group

Allow:

- MySQL (3306) from EC2 Security Group only

---

## Step 3: Create S3 Static Website

1. Create S3 Bucket
2. Enable Static Website Hosting
3. Upload HTML, CSS and JavaScript files
4. Configure Bucket Policy

---

## Step 4: Launch EC2 Instance

1. Launch Amazon Linux 2 Instance
2. Install Apache/Nginx
3. Deploy Application Code
4. Verify Application Access

---

## Step 5: Create RDS Database

1. Create MySQL RDS Instance
2. Configure Private Subnet
3. Configure Security Group
4. Save Endpoint Information

---

## Step 6: Connect Application to Database

Update application configuration:

- Database Endpoint
- Username
- Password
- Database Name

---

## Step 7: Configure Route 53

1. Register Domain
2. Create Hosted Zone
3. Create DNS Records
4. Point Domain to Application

---

## Testing

- Verify S3 Website
- Verify EC2 Application
- Verify RDS Connectivity
- Verify End-to-End Data Flow

---

## Outcome

Successfully deployed a secure AWS 3-Tier Architecture using AWS native services.
