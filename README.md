# Automation with CloudFormation

## Overview

In this project, we demonstrate how to deploy and manage infrastructure in a consistent, reliable manner using AWS CloudFormation. CloudFormation allows us to define resources in templates, which can then be automatically deployed, even on a schedule. The tasks in this project guide you through deploying a Virtual Private Cloud (VPC), adding resources like S3 buckets and EC2 instances, and managing CloudFormation stacks.

This project consists of three primary tasks:
- **Task 1**: Deploy a CloudFormation stack with a VPC and security group.
- **Task 2**: Update the stack by adding an Amazon S3 bucket.
- **Task 3**: Add an Amazon EC2 instance to the stack.

## Technologies Used
- AWS CloudFormation
- Amazon EC2
- Amazon S3
- AWS VPC
- YAML for CloudFormation templates

## Task Details

### Task 1: Deploy a CloudFormation Stack
In this task, we deploy a CloudFormation stack that defines a VPC, subnet, and security group. The stack can be deployed with just a few clicks in the AWS Management Console.

### Task 2: Add an Amazon S3 Bucket
In this task, we edit the CloudFormation template to add an Amazon S3 bucket to the stack. The stack is then updated with the new template, and the S3 bucket is deployed automatically.

### Task 3: Add an Amazon EC2 Instance
The final task demonstrates how to add an EC2 instance to the stack by modifying the CloudFormation template. The EC2 instance is launched using the latest Amazon Linux AMI, and security groups and subnets are correctly configured.

## Getting Started

### Prerequisites
- AWS Account with appropriate permissions to use CloudFormation, EC2, and S3.
- Basic understanding of YAML and CloudFormation templates.

### Running the Project
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yasnai1/automation-with-cloudformation.git
