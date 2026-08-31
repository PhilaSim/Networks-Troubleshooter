# Networks-Troubleshooter

A practical Infrastructure as Code project for deploying and configuring an AWS EC2 web server with Terraform.

## Overview

**Networks-Troubleshooter** demonstrates how cloud infrastructure can be defined, configured, and reproduced using **Terraform**. The project is useful for learning AWS networking fundamentals, EC2 provisioning, security groups, and infrastructure automation.

## What It Does

- Provisions an AWS EC2 instance
- Uses a configurable AMI and instance type
- Supports an optional security group
- Allows SSH and HTTP access when configured
- Supports EC2 key-pair authentication
- Demonstrates Infrastructure as Code with Terraform

## Tech Stack

- **Terraform** — Infrastructure as Code
- **AWS EC2** — Compute
- **AWS Security Groups** — Network access control

## Prerequisites

Before using the project, make sure you have:

- An AWS account
- Terraform installed
- AWS credentials configured securely
- An appropriate EC2 key pair

## Getting Started

Clone the repository:

```bash
git clone https://github.com/PhilaSim/Networks-Troubleshooter.git
cd Networks-Troubleshooter
```

Initialize Terraform:

```bash
terraform init
```

Review the planned infrastructure:

```bash
terraform plan
```

Apply the configuration:

```bash
terraform apply
```

When you are finished, remove resources that are no longer needed:

```bash
terraform destroy
```

## Security Notes

Never commit AWS access keys, private SSH keys, `.tfstate` files containing sensitive information, or other secrets to GitHub. Use environment variables, AWS credential profiles, or an appropriate secrets-management solution instead.

## Project Goals

- Practice AWS infrastructure provisioning
- Understand Terraform workflows
- Explore EC2 networking and security groups
- Build repeatable cloud infrastructure

## Contributing

Suggestions, bug reports, and improvements are welcome. Open an issue or submit a pull request with a clear description of the proposed change.

## License

No license has been specified for this repository yet.

---

Built by **PhilaSim**.