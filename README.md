# AWS Multi-Tier Website Deployment Project
This project demonstrates how to deploy a scalable, fault-tolerant, multi-tier web application on AWS using services like EC2, RDS (MySQL), Load Balancer, and Auto Scaling Group.

## Technologies & Services Used

- Amazon EC2 (Elastic Compute Cloud)
- Security Groups & SSH Access
- Apache Web Server & PHP
- Amazon RDS (MySQL)
- Application Load Balancer
- Auto Scaling Group
- Route 53 DNS Mapping

## Key Features

- Web server setup using EC2 and Apache
- Database hosted on Amazon RDS (MySQL)
- Scalable infrastructure using Auto Scaling Group
- High availability via Load Balancer
- Domain name configured using Route 53

## Deployment Steps Summary

1. Launched and configured EC2 instances.
2. Installed Apache2, PHP, and MySQL Client on EC2.
3. Set up MySQL RDS instance with public access.
4. Created database and tables on RDS.
5. Deployed website files to EC2 using FileZilla.
6. Created AMI and Launch Template.
7. Configured Auto Scaling Group and Application Load Balancer.
8. Mapped domain name to Load Balancer using Route 53.

## Outcome

- Successfully deployed a highly available, multi-tier web application on AWS.
- Verified public access to the application via domain name.
