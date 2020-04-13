# TERRAFORM-AWS-VPC
Terraform module which create VPC on AWS Cloud

## Description
Provision VPC, Subnets, Route table, Internet GW, NAT GW

## Usage

### Minimal

```terraform
module "aws_vpc" {
  source               = git::https://github.com/bellyliu/terraform-aws-vpc.git
  vpc_name             = " "
  cidr_block           = [ "" ]
  enable_dns_hostnames = true / false
  enable_dns_support   = true / false
}
```

# Terraform Version
0.12.24