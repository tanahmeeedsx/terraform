# Terraform — AWS EC2 Provisioning

A beginner-friendly Terraform project demonstrating how to provision and manage AWS EC2 infrastructure using Infrastructure as Code (IaC).

## Overview

This project uses Terraform to automate AWS EC2 instance provisioning, making infrastructure deployment repeatable, consistent, and easy to manage.

## Tech Stack

- **Terraform** — Infrastructure as Code
- **AWS** — Cloud Infrastructure
- **Amazon EC2** — Virtual Machine
- **HCL** — HashiCorp Configuration Language
- **AWS CLI** — AWS Account Authentication

## Project Structure

```text
terraform/
├── main.tf
├── output.tf
├── .terraform.lock.hcl
└── .gitignore
```

## Prerequisites

- Terraform CLI installed
- AWS CLI installed
- AWS account
- AWS credentials configured

## Getting Started

**1. Clone the repository**

```bash
git clone https://github.com/tanahmeeedsx/terraform.git
cd terraform
```

**2. Initialize Terraform**

```bash
terraform init
```

**3. Validate the configuration**

```bash
terraform validate
```

**4. Review the execution plan**

```bash
terraform plan
```

**5. Deploy the infrastructure**

```bash
terraform apply
```

Review the proposed changes and type `yes` to confirm.

**6. View Terraform outputs**

```bash
terraform output
```

## Cleanup

To remove the provisioned AWS infrastructure:

```bash
terraform destroy
```

Review the proposed deletions and confirm before proceeding.

## Key Learnings

- Understanding Infrastructure as Code (IaC)
- Configuring AWS providers in Terraform
- Provisioning EC2 instances
- Managing infrastructure lifecycle
- Using Terraform initialization, validation, planning, and execution
- Understanding Terraform state management

## Cost Considerations

AWS resources may incur charges depending on your account, region, and resource configuration. Always verify resource eligibility and pricing, and destroy unused infrastructure.

**Never commit AWS credentials or Terraform state files to GitHub.**

## Author

**Tanjim Ahmed**

GitHub: [@tanahmeeedsx](https://github.com/tanahmeeedsx)
