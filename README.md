# Terraform AWS Basics

My first Infrastructure as Code project: a Terraform config that creates an S3 bucket on AWS.

## What it does

- Uses the AWS provider in us-east-1
- Creates one S3 bucket

## How to run it

```bash
terraform init
terraform plan
terraform apply
terraform destroy   # clean up when done
```

## What I learned

- Plan before apply, destroy when done
- Keep state files and credentials out of Git
