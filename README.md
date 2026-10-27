# AWS Order Management System
AWS Order Management System using EC2, S3, Lambda, RDS, IAM, VPC, and CloudWatch for application hosting, order processing, database storage, access control, and monitoring.
# AWS Order Management System

## Project Overview
This project demonstrates an AWS-based order management system designed to explore application hosting, order processing, database storage, access management, networking, and monitoring using AWS services.

## AWS Services
- **Amazon EC2:** Hosts the application server.
- **Amazon S3:** Provides object storage for order-related files.
- **AWS Lambda:** Supports serverless order-processing logic.
- **Amazon RDS (MySQL):** Stores order information in a relational database.
- **AWS IAM:** Manages access permissions for AWS resources.
- **Amazon VPC:** Provides network isolation and connectivity.
- **Amazon CloudWatch:** Monitors metrics and supports alarm configuration.

## Architecture
The planned workflow is:

1. The application runs on an EC2 instance.
2. Order-related files are stored in S3.
3. Lambda processes order-related operations.
4. RDS stores order information.
5. IAM controls access to AWS resources.
6. VPC provides network isolation.
7. CloudWatch monitors infrastructure metrics and configured alarms.

## Implementation Status
AWS resources have been created and configured as part of this project. Lambda-to-RDS integration and end-to-end application testing are still in progress.

## Skills Demonstrated
- AWS infrastructure configuration through the AWS Management Console
- EC2 instance management
- VPC and security group configuration
- S3 object storage
- IAM roles and permissions
- Lambda and RDS integration
- CloudWatch metrics and alarms

## Future Improvements
- Complete and test Lambda-to-RDS connectivity.
- Implement and test order-processing functionality.
- Validate end-to-end application behavior.

## Author
Shubham Sharma

GitHub: https://github.com/iamshubham2001
