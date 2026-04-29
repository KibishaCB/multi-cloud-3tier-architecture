# Multi-Cloud 3-Tier Architecture (AWS + Azure)

## Overview
This project demonstrates a real-time multi-cloud 3-tier architecture deployed across AWS and Azure, ensuring scalability, high availability, and secure communication between services.

- ☁️ AWS → Web & Application Layer
- ☁️ Azure → Database Layer

## Architecture
- Presentation Layer (Frontend):
  -AWS EC2 (Nginx/Apache)
  -Application Load Balancer (ALB)

- Application Layer:
  -AWS EC2 (Auto Scaling Group)
  -Hosted in private subnet

- Database Layer:
   -Azure MySQL Database
   -Secured using firewall rules

## Features
- High availability using Auto Scaling
- Load balancing using ALB
- Secure database access across cloud platforms
- Multi-cloud architecture design
- Scalable and fault-tolerant system

## Technologies Used
  - AWS: EC2, VPC, ALB, Auto Scaling
  - Azure: Azure MySQL Database, Virtual Network
  - Other: Linux, PHP

## Security Implementation
- AWS Security Groups for controlled access
- Azure firewall rules for database protection
- Private subnet for application layer
- Principle of least privilege

## Implementation Steps
   1.Created AWS VPC with public and private subnets
   2.Deployed EC2 instances for web and application layers
   3.Configured Application Load Balancer
   4.set up Azure MySQL database
   5.Connected AWS application to Azure database
   6.Tested end-to-end connectivity

##Outcome
    Successfully deployed a scalable, secure, and highly available multi-cloud application, demonstrating real-world cloud architecture skills.
