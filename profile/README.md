# Husky Profile

Part of Coursework: CSYE 6225 - Network Structures and Cloud Computing

## Description

Husky Profile is a node.js scalable application developed and deployed in AWS Platform using CloudFormation and other resources like S3, Lambda functions, SNS, SES etc. <br/>
This application allows northeastern community members to provide their basic profile details.

## Repositories

1. webservice - for nodejs javascript backend code
2. infrastructure - for cloudformation infrastructure as code
3. serverless - for lambda function
<br/>(for links please scroll down)

## AWS Resources Used

* **CloudFormation** for **IaC**
* **VPC, Subnets, Route Tables, Internet Gateway, Security Groups**
* **EC2 scalable instances, AMI, EBS, ASG, Load Balancer**
* **IAM, User groups, Users, Roles, Policies**
* **CodeDeploy**
* **Route53** for DNS
* **S3** secure storage for profile pictures
* **RDS** for other profile details
* **DynamoDB** with TTL for handling one-time-use tokens
* **SES** for email notifications
* **Lambda** function for sending time-sensitive verification emails via SES
* **SNS** for triggering Lambda functions
* **CloudWatch** for logging data & monitoring metrics
* **KMS** for encryption keys
* **Secrets Manager** for storing secrets
* **ACM** for HTTPS certificate managing
* **GitHub Actions** for streamlining **CI/CD** pipelines 


## Technologies Used

AWS, Cloudformation (IaC), Node.js, JavaScript, Express.js, PostgreSQL, Linux commands, GitHub Actions (CI/CD)

## Me

Vignesh Gunasekaran<br/>
MS, Information Systems<br/>
Northeastern University
