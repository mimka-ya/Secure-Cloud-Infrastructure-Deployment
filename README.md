# Secure-Cloud-Infrastructure-Deployment
Secure-Cloud-Infrastructure-Project

Project Description: Cloud Infrastructure for XCorp Red Team

Introduction: This project sets up a highly available web server infrastructure on Azure for XCorp’s Red Team, supporting testing and training activities.

Cloud Setup Overview: The setup includes an Azure Resource Group containing a Virtual Network (VNet) with designated IP ranges and subnets. Multiple Virtual Machines (VMs) are deployed within this environment to host Damn Vulnerable Web Application (DVWA), ensuring redundancy and load balancing.

Components and Functionality: Docker containers are used on each VM to efficiently manage DVWA instances. Ansible automation, integrated via an Ansible Jump Box, streamlines configuration management across the infrastructure.

Traffic and Security: A Load Balancer manages traffic, directing HTTP requests to DVWA instances. Strict security measures, including configured security groups, control SSH access to ensure secure administrative interactions.

Conclusion and Significance: This project establishes a robust, scalable web server infrastructure, enhancing XCorp’s testing and training capabilities. By leveraging Docker for containerization and Ansible for automation, the solution ensures operational efficiency and flexibility in managing the cloud environment.






