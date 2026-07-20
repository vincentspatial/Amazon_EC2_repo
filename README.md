# AWS EC2 PROJECT
# AWS EC2 Web Server Deployment Project

## OVERVIEW
This project deostrates how to provision, configure, secure, and deploy a Web server using an Amazon EC2 virtual machine.

The goal was to gain practical experience with AWS compute services, Linux server administration, networking, security groups, SSH access, and web server deployment.

## Project Objectives
- Understand the process of launching an EC2 instance
- Configure secure remote access using SSH
- Manage inbound traffic using Security Groups
- Install and configure an Apache web server
-  Host a static webpage on a cloud-based virtual server
       
 ### Tasks Completed
  - Created and configured AWS account
  - Created EC2 key pair for secure SSH authentication
  - Configured Security Group rules (SSH and HTTP access)
  - Launched an Amazon Linux EC2 instance
  - Connected to the instance using SSH
  - Installed Apache Web Server
  - Started and enabled Apache service
  - Created and hosted a simple HTML webpage
       
 ### Architecture
       
 User - Internet - AWS Security Group - EC2 Instance - Apache Web Server - Hosted Webpage
       
 ## Technologies Used
  -  AWS EC2
  - Amazon Linux
  - Linux Command Line
  - SSH
  - Apache HTTP Server
  - HTML
                   
   ## Commands Used
   - Update server packages:
                   
      - ```bash
      - sudo dnf update -y
      - sudo dnf install httpd -y
      - sudo systemctl start httpd
      - sudo systemctl enable httpd
