# **High-Availability PHP Application Deployment on AWS**  
[![AWS](https://img.shields.io/badge/AWS-Cloud-orange)](https://aws.amazon.com/)  
[![PHP](https://img.shields.io/badge/PHP-7.4%2B-blue)](https://www.php.net/)  
[![MySQL](https://img.shields.io/badge/MySQL-8.0-green)](https://www.mysql.com/)  

---

## **Project Overview**  
This project involved designing and deploying a **highly available PHP application** for a social research company on **AWS**. The architecture ensures **scalability**, **fault tolerance**, and **secure access** to resources.  

---

## **Key Features**  
- **Scalable Architecture**:  
  - Utilized **Amazon EC2**, **RDS (MySQL)**, **Application Load Balancer (ALB)**, and **Auto Scaling Groups** to handle dynamic traffic loads.  
- **Automated Deployment**:  
  - Created **AWS Launch Templates** to automate web server setup, including **Apache HTTPD**, **MySQL**, and application code deployment.  
- **Secure Configuration**:  
  - Managed database credentials securely using **AWS Systems Manager Parameter Store**.  
  - Implemented **bastion host access** for secure database management.  
- **High Availability**:  
  - Achieved fault tolerance through **multi-AZ RDS deployment** and **auto-scaling** for web servers.  

---

## **Architecture Diagram**  
![Architecture Diagram](https://github.com/user-attachments/assets/635d0879-99e8-4377-961c-58dc2e38005b)  

---

## **Technologies Used**  
- **AWS Services**:  
  - **EC2**: Virtual servers for hosting the PHP application.  
  - **RDS (MySQL)**: Managed relational database service.  
  - **ALB (Application Load Balancer)**: Distributes incoming traffic across multiple EC2 instances.  
  - **Auto Scaling**: Automatically adjusts the number of EC2 instances based on traffic.  
  - **Systems Manager Parameter Store**: Securely stores and manages configuration data.  
- **Web Stack**:  
  - **PHP**: Server-side scripting language for the application.  
  - **Apache HTTPD**: Web server software.  
  - **MySQL**: Database management system.  

---

## **Installation and Deployment**  

### **1. Prerequisites**  
- An **AWS account** with necessary permissions.  
- **AWS CLI** installed and configured.  

### **2. Clone the Repository**  
```bash  
git clone https://github.com/your-username/High-Availability-PHP-Application-Deployment-on-AWS.git  
cd High-Availability-PHP-Application-Deployment-on-AWS  
