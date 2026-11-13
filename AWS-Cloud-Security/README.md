# AWS Cloud Security Architecture Project

## Project Overview
For this project, I designed a secure AWS cloud architecture for a fictional company called WinLocal Giveaways following a ransomware incident.

The aim was to improve network security, protect customer information and make the company's systems more reliable.

## Tools and Technologies
- Amazon Web Services (AWS)
- VPC and public/private subnets
- EC2 instances
- Security Groups
- Bastion Host and SSH
- Application Load Balancer
- Amazon S3
- AWS CloudTrail
- NIST Cybersecurity Framework 2.0

## What I Did
I designed a three-tier cloud architecture and completed a practical proof of concept using AWS.

### 1. Network Configuration
I created a VPC with four subnets across two Availability Zones to separate public and private resources.

### 2. Security Groups
I configured security groups to control access to the servers and restrict administrative SSH connections.

### 3. Bastion Host
I configured and tested SSH access to a bastion host for secure administration.

### 4. Web Server
I deployed a web server on an EC2 instance and documented the use of an Application Load Balancer.

### 5. S3 Backup Website
I created a static maintenance website using Amazon S3 to provide information during downtime.

### 6. Monitoring
I documented AWS CloudTrail for tracking activity within the cloud environment.

## Results
- Created a VPC with public and private subnets.
- Configured network access restrictions using security groups.
- Successfully connected to the bastion host using SSH.
- Demonstrated a working web server and S3 maintenance page.
- Designed additional security and availability measures.

## Limitations
The Auto Scaling Group could not be created because of environment restrictions. The RDS database was included in the proposed design but was not implemented in the proof of concept.

## Skills Developed
- AWS cloud architecture
- Network segmentation
- Access control and least privilege
- Secure remote administration
- Cloud security design
- Technical documentation

## Project Evidence
The project report contains architecture diagrams, AWS configuration screenshots and implementation results.
