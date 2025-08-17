# Dream Vacation App

## Project Overview
This project deploys a Dream Vacation App to EC2 using AWS infrastructure and CI/CD pipeline.

## Infrastructure
- VPC: dream-vpc (10.0.0.0/16)
- Subnet: dream-subnet (10.0.1.0/24)
- Internet Gateway: dream-igw
- Route Table: dream-rt
- EC2 Instance: Ubuntu t3.micro

## Deployment
- Containerized with Docker
- CI/CD pipeline with GitHub Actions
- Successfully deployed and tested

## Screenshots

### VPC and Subnet Configuration
![VPC and Subnet](screenshots/vpc-subnet.png)

### EC2 Instance Running
![EC2 Instance](screenshots/ec2-running.png)

### Application Running in Browser
![App in Browser](screenshots/app-browser.png)

### CI/CD Pipeline Successful Deployment
![CI/CD Pipeline](screenshots/cicd-pipeline.png)

## Deliverables
- ✅ VPC and subnet configured in AWS Console
- ✅ EC2 instance running screenshot
- ✅ App running in browser
- ✅ CI/CD pipeline implemented