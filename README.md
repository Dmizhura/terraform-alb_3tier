# Terraform Ecommerce 3 Tier Architecture Project

![Alt text](terraform-ecommerce.jpg)

This project is a comprehensive DevOps initiative aimed at hosting a dynamic ecommerce web application on Amazon Web Services (AWS) with terraform. Below is an outline of the resources utilized along with a brief description of their roles in the deployment process.

## Resources Utilized
**Terraform**: Infrastructure as code tool that lets you define cloud resources in human-readable configuration files that you can version, reuse, and share.
**Git**: Employed for version control to track changes to source code and files.
**GitHub**: Used to manage Dockerfiles and application code in Git repositories.
**AWS CLI**: Enabled interaction with AWS services via the command line.
**Visual Studio Code (VS Code)**: Chosen as the integrated development environment for writing and editing scripts.
**3 Tier VPC (Virtual Private Cloud)**: Configured with public and private subnets across two availability zones.
**Internet Gateway**: Facilitated communications between VPC resources and the internet.
**NAT Gateway**: Enabled resources in private subnets to access the internet.
**Amazon RDS (Relational Database Service)**: Utilized for the relational database.
**Application Load Balancer**: Utilized for distributing web traffic to ECS Fargate tasks.
**Auto Scaling Group**: Dynamically created new ECS tasks as required.
**Route 53**: Registered domain names and created record sets for DNS management.
**Amazon S3**: Stored files and container environment variables.
**IAM Role**: Granted permissions for ECS to execute tasks.
**Security Groups**: Controlled inbound and outbound traffic to resources.
**Certificate Manager**: Employed for encrypting data in transit.
**SNS Topic**: Deployed to provide notifcations of AWS resources.

## Project Files
- **Deployment Scripts**: Available in the repository

## Contributing
Contributions to improve this project are welcome. Please submit a pull request.
