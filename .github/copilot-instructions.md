# Copilot Instructions for test-ecommerce-suite Infrastructure (AWS)

This is the AWS infrastructure repository for test-ecommerce-suite.

## Tech Stack

- Terraform
- AWS
- tflint for linting

## Available Agents

| Agent | Purpose |
|-------|---------|
| `@terraform` | Terraform best practices |
| `@aws` | AWS resource patterns |
| `@security` | Security review |

## Commands

```bash
terraform init       # Initialize
terraform plan       # Preview changes
terraform apply      # Apply changes
terraform validate   # Validate config
tflint              # Lint
```

## Project Structure

```
terraform/
├── environments/    # Per-environment configs
│   ├── dev/
│   ├── staging/
│   └── prod/
├── modules/        # Reusable modules
└── shared/         # Shared resources
```
