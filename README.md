# AWS Order Management System

An AWS-based Order Management System designed to demonstrate cloud infrastructure deployment, serverless processing, database integration, secure access management, and infrastructure monitoring using core AWS services.

## Project Overview

This project demonstrates how to design and deploy an order management solution using Amazon EC2, Amazon S3, AWS Lambda, Amazon RDS, AWS IAM, Amazon VPC, and Amazon CloudWatch.

The architecture separates application hosting, order-processing logic, database storage, and monitoring to provide a structured and maintainable cloud solution.

## AWS Services Used

| AWS Service | Purpose |
|---|---|
| Amazon EC2 | Hosts the application server |
| Amazon S3 | Stores order-related files and objects |
| AWS Lambda | Executes serverless order-processing logic |
| Amazon RDS (MySQL) | Stores order information in a relational database |
| AWS IAM | Manages permissions and access to AWS resources |
| Amazon VPC | Provides network isolation and subnet configuration |
| Amazon CloudWatch | Monitors resource metrics and configured alarms |

## Architecture

The solution uses a VPC with separate public and private subnets to organize application and database-related resources.

**Architecture components:**
- **Public subnet:** Hosts the EC2 application server.
- **Private subnet:** Provides a network location for private resources and serverless database connectivity.
- **EC2:** Provides the application hosting environment.
- **Lambda:** Handles serverless order-processing operations.
- **RDS MySQL:** Provides relational storage for order records.
- **S3:** Stores order-related files.
- **IAM:** Controls access through roles and permissions.
- **CloudWatch:** Supports monitoring, logs, metrics, and alarms.

### Architecture Diagram

![AWS Order Management System Architecture](AWS%20Order%20Management%20Architecture.png)

## Application Workflow

1. The application runs on the EC2 instance.
2. Order-related files can be stored in Amazon S3.
3. AWS Lambda executes the order-processing logic.
4. Amazon RDS MySQL stores structured order information.
5. IAM roles and policies control access to AWS resources.
6. The VPC and subnet configuration provide network separation.
7. CloudWatch monitors supported resource metrics and configured alarms.

## Infrastructure Configuration

The project includes configuration of the following AWS resources:

- Custom VPC with public and private subnets.
- Internet Gateway and public route table.
- EC2 instance with security group restrictions.
- Amazon RDS MySQL database.
- Lambda function with VPC configuration.
- IAM permissions for AWS resource access.
- CloudWatch CPU utilization alarm.

## Key Skills Demonstrated

- AWS infrastructure configuration through the AWS Management Console
- VPC networking, subnets, route tables, and Internet Gateway
- EC2 provisioning and Linux server administration
- Security groups and IAM access management
- Amazon S3 object storage
- AWS Lambda fundamentals
- Amazon RDS MySQL configuration
- CloudWatch monitoring and alarms
- Cloud infrastructure troubleshooting

## Project Goals

- Build an AWS-based order management architecture.
- Separate application hosting and database resources.
- Explore serverless processing and database connectivity.
- Apply AWS networking and access-control principles.
- Configure monitoring for cloud resources.

## Author

**Shubham Sharma**

GitHub: [iamshubham2001](https://github.com/iamshubham2001)
