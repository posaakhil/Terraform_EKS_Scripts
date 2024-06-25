# terraform EKS

This repository provides a sample setup to create an EKS (Elastic Kubernetes Service) cluster on AWS using Terraform.

## Prerequisites

### Install AWS CLI

Before you begin, ensure you have the AWS CLI installed. Follow the instructions [here](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html) to install the AWS CLI.

### Install Terraform

Next, install Terraform by following the steps outlined [here](https://learn.hashicorp.com/tutorials/terraform/aws-build?in=terraform/aws-get-started).

## Connect Terraform with AWS

Once AWS CLI and Terraform are installed, connect Terraform with AWS by running:
```bash
aws configure

git clone <repository-url>
cd terraform-eks
## Initialize Terraform:
terraform init
## Review Terraform Configuration (Optional)
terraform plan
## Apply Terraform Configuration to Create EKS Cluster with VPC
 terraform apply
