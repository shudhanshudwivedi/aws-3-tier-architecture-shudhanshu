# AWS 3-Tier Architecture Diagram

## Architecture Flow

User
  │
  ▼
Route 53
  │
  ▼
Amazon S3 (Frontend)
  │
  ▼
Amazon EC2 (Backend)
  │
  ▼
Amazon RDS (Database)

---

## Components

### Route 53
Provides DNS and domain routing.

### Amazon S3
Hosts static website content.

### Amazon EC2
Runs application services and business logic.

### Amazon RDS
Stores application data securely.

### Amazon VPC
Provides network isolation and security.

---

## Security Features

- IAM Roles
- Security Groups
- Private Subnets
- Least Privilege Access

---

## High Availability

- Scalable Architecture
- Managed Database Service
- Reliable AWS Infrastructure
