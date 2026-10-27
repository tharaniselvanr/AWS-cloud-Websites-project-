# AWS-cloud-Websites-project-
AWS Cloud-Based Website Hosting with Database, Storage and Monitoring.
                    

   
                    USER
                      ↓
          Application Load Balancer
                      ↓
                    EC2
               PHP Website
                 ↙       ↘
            RDS MySQL     S3
            Database     Storage
                 ↘       ↙
                CloudWatch
                 Monitoring
AWS Services Used

- VPC – Created the private network environment.
- EC2 – Hosted and ran the PHP website.
- Application Load Balancer (ALB) –  Distributed incoming user requests to the EC2 server.
- RDS MySQL – Stored and managed the website database.
- S3 – Used for file and object storage.
- CloudWatch – Monitored AWS resources and performance.

Project Flow

1. User sends a request to access the website.
2. Application Load Balancer receives the request and forwards it to the EC2 instance.
3. The PHP website runs on the EC2 server.
4. The website uses RDS MySQL for database operations.
5. S3 is used for storing files and objects.
6. CloudWatch monitors the AWS resources and their performance.

Project Objective

The main objective of this project is to host a dynamic PHP website on AWS with database connectivity, storage, load balancing, and monitoring.

This project demonstrates how different AWS services can work together to provide a reliable and scalable cloud-based website.
