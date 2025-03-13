# High-Availability-PHP-Application-Deployment-on-AWS
This project involved designing and deploying a highly available PHP application for a social research company on AWS. The architecture ensures scalability, fault tolerance, and secure access to resources.

Key Features

Scalable Architecture: Utilized Amazon EC2, RDS (MySQL), Application Load Balancer (ALB), and Auto Scaling Groups to handle dynamic traffic loads.
Automated Deployment: Created AWS Launch Templates to automate web server setup, including Apache HTTPD, MySQL, and application code deployment.
Secure Configuration: Managed database credentials securely using AWS Systems Manager Parameter Store and implemented bastion host access for secure database management.
High Availability: Achieved fault tolerance through multi-AZ RDS deployment and auto-scaling for web servers.

Architecture Diagram
![image](https://github.com/user-attachments/assets/635d0879-99e8-4377-961c-58dc2e38005b)

Technologies Used

AWS (EC2, RDS, ALB, Auto Scaling, Systems Manager)
PHP, MySQL, Apache HTTPD
