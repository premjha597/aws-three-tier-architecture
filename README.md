 AWS Three-Tier Architecture

A production-style Three-Tier Architecture deployed on Amazon Web Services (AWS) demonstrating secure networking, load balancing, private application hosting, and managed database integration.


 Project Overview

This project demonstrates how to build a secure and scalable three-tier application architecture using AWS.

The architecture separates the application into three layers:

- Presentation Layer (Web Server)
- Application Layer (Private EC2)
- Database Layer (Amazon RDS)


AWS Services Used

- Amazon VPC
- Public Subnets
- Private Subnets
- Internet Gateway
- NAT Gateway
- Route Tables
- Security Groups
- Application Load Balancer (ALB)
- Target Groups
- Amazon EC2
- Amazon RDS (MySQL)

---

# 🏛️ Architecture

```
                    Internet
                         │
                         ▼
             Application Load Balancer
                         │
                         ▼
                Public EC2 (Web Server)
                         │
                  Private Communication
                         │
                         ▼
           Private EC2 (Application Server)
                         │
                   MySQL Port 3306
                         │
                         ▼
                Amazon RDS (MySQL)
```

Author

Prem Jha


