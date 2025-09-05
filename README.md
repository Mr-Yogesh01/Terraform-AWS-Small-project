# Terraform-AWS-Small-projec

# AWS + Terraform Project (Basic EC2)

This project deploys an **EC2 instance** on AWS using Terraform.

## Steps to Run

1. Install Terraform: https://developer.hashicorp.com/terraform/downloads
2. Configure AWS CLI:
   ```bash
   aws configure

terraform init

terraform plan

terraform apply -auto-approve

terraform output ec2_public_ip

