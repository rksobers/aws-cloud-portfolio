# Scale Watch

## Project Goal

Scale Watch demonstrates a scalable AWS web application architecture using Amazon EC2, an Application Load Balancer, Amazon RDS, and IAM. The project focuses on scalability, high availability, and foundational cloud design principles.

## Architecture

[Architecture v1](diagrams/architecture-v1.md)

## AWS Services

- Amazon EC2
- Application Load Balancer (ALB)
- Amazon RDS
- IAM

## Project Objectives

- Deploy EC2 instances
- Configure an Application Load Balancer
- Connect EC2 instances to Amazon RDS
- Implement IAM best practices
- Design for scalability and high availability

## Progress

- [x] Architecture Design
- [x] VPC Configuration
- [ ] EC2 Deployment
- [ ] Application Load Balancer
- [ ] Amazon RDS
- [ ] IAM Configuration
- [ ] End-to-End Testing
- [ ] Cost Analysis
- [ ] Documentation Complete

---

## Completed Milestones

### Step 1 – Virtual Private Cloud (VPC)

**Objective**

Create an isolated virtual network that will host all Scale Watch resources.

**Configuration**

| Setting | Value |
|---------|-------|
| Name | scale-watch-vpc |
| Region | us-west-2 (Oregon) |
| IPv4 CIDR | 10.0.0.0/16 |
| Tenancy | Default |

**Evidence**

![VPC Created](screenshots/01-vpc-created.png)

**What I Learned**

- A VPC is the logical network boundary for AWS resources.
- Availability Zones exist inside a Region.
- All networking resources for Scale Watch will be deployed inside this VPC.


## Repository Structure

```
scale-watch/
├── README.md
├── diagrams/
├── screenshots/
├── templates/
└── notes/
```

## Notes

This project demonstrates the design and implementation of a scalable AWS web application using EC2, an Application Load Balancer, Amazon RDS, and IAM.
