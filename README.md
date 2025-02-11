# Secure-Cloud-Infrastructure-Deployment 

## Project Description: Cloud Infrastructure for XCorp Red Team

**Introduction:**  
This project involves setting up a highly available web server infrastructure on Azure for XCorp’s Red Team. The infrastructure supports their testing and training activities, providing a secure environment for simulations and exercises.

## Cloud Setup Overview:  
The setup consists of an Azure Resource Group that contains a Virtual Network (VNet) with designated IP ranges and subnets. Multiple Virtual Machines (VMs) are deployed to host the Damn Vulnerable Web Application (DVWA), ensuring redundancy and load balancing to maintain high availability.

## Components and Functionality:  
Each VM hosts Docker containers that efficiently manage DVWA instances, improving scalability and resource utilization. Ansible is integrated via an Ansible Jump Box to streamline the configuration management process, ensuring consistency across the infrastructure.

## Traffic and Security:  
A Load Balancer directs HTTP requests to the DVWA instances, ensuring even traffic distribution across the VMs. Strict security measures, including well-configured security groups, control SSH access to the VMs, ensuring secure administrative interactions and minimizing potential attack vectors.

## Conclusion and Significance:  
This project establishes a robust, scalable web server infrastructure for XCorp's Red Team, enhancing their ability to perform testing and training activities. By leveraging Docker for containerization and Ansible for automation, the solution maximizes operational efficiency and flexibility, ensuring seamless management of the cloud environment.

![Alt text](https://github.com/mimka-ya/Secure-Cloud-Infrastructure-Deployment/blob/main/MYaroshenko_CloudSecurity.png)
