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
