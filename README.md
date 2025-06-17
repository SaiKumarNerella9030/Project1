Project Goal
Use Terraform to provision a production-ready architecture

Tools Used:
Terraform

AWS (VPC, Subnets, EC2, ALB, RDS, Security Groups)

Remote backend (S3 + DynamoDB) – optional but recommended

terraform-multi-tier/
├── main.tf
├── variables.tf
├── outputs.tf
├── modules/
│   ├── vpc/
│   ├── ec2/
│   ├── rds/
│   └── alb/
