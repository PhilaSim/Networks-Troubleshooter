# Networks-Troubleshooter

> An Infrastructure as Code project for provisioning and configuring AWS EC2 infrastructure with Terraform.

## Overview

**Networks-Troubleshooter** demonstrates how cloud infrastructure can be defined, provisioned, and managed through Terraform. The project focuses on AWS compute, network access, security groups, key-pair authentication, and repeatable infrastructure workflows.

## Architecture

The project provisions an **AWS EC2 instance** and supports configurable infrastructure parameters. Network access can be controlled through an AWS security group, including SSH and HTTP access where configured.

## Technology Stack

| Technology | Role |
|---|---|
| Terraform | Infrastructure as Code |
| AWS EC2 | Compute infrastructure |
| AWS Security Groups | Network access control |

## Prerequisites

Before deploying, ensure you have:

- An AWS account
- Terraform installed
- Securely configured AWS credentials
- An appropriate EC2 key pair
- Permissions to create and manage the required AWS resources

## Deployment

Clone the repository:

```bash
git clone https://github.com/PhilaSim/Networks-Troubleshooter.git
cd Networks-Troubleshooter
```

Initialize Terraform:

```bash
terraform init
```

Review the proposed infrastructure:

```bash
terraform plan
```

Apply the configuration:

```bash
terraform apply
```

Remove the provisioned resources when they are no longer required:

```bash
terraform destroy
```

## Security

Never commit credentials or sensitive infrastructure data to GitHub. In particular, do not commit:

- AWS access keys or secret keys
- Private SSH keys
- Sensitive Terraform state files
- API credentials or other secrets

Use secure credential profiles, environment variables, or a dedicated secrets-management solution instead.

## Learning Objectives

- Practice Infrastructure as Code with Terraform
- Provision AWS compute resources
- Understand EC2 networking and security groups
- Build repeatable cloud infrastructure workflows
- Apply basic cloud-security principles

## Contributing

Contributions and suggestions are welcome. Open an issue for significant changes or submit a pull request with a clear description of the proposed improvement.

## License

No license has been specified for this repository.

## Author

**PhilaSim**