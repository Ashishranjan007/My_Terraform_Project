# My_Terraform_Project

Welcome to the repository for My Terraform Project. This project uses Terraform to manage and deploy infrastructure on AWS.

## Project Overview

This Terraform project sets up an AWS infrastructure including:
- VPC
- Subnets
- S3 bucket
- EC2 instances
- Auto LoadBalancer

## Prerequisites

Before you begin, ensure you have met the following requirements:
- You have installed [Terraform](https://www.terraform.io/downloads.html)
- You have an AWS account and your AWS credentials are configured (`aws configure`)


## Resources

Here are some resources to help you with Terraform and AWS:

[Terraform Documentation](
[AWS Documentation](https://docs.aws.amazon.com/)
Terraform AWS Provider Documentation




## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Ashishranjan007/My_Terraform_Project.git
   cd My_Terraform_Project

2. Initialize Terraform:

   ```bash
   terraform init

3. Preview the changes Terraform will make to your infrastructure:

   ```bash
   terraform plan

4. Apply the Terraform configuration to create the infrastructure:

    ```bash
    terraform apply -auto-approve
Type yes when prompted to confirm the action.

4. To destroy the infrastructure when you no longer need it:

   ```bash
   terraform destroy -auto-approve
