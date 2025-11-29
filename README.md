# test-ecommerce-suite - Infrastructure

Infrastructure repository for the test-ecommerce-suite project.

## 📊 Project Tracking

| Resource | Link |
|----------|------|
| **GitHub Project** | [test-ecommerce-suite-project](https://github.com/users/mdizcalvinoaz400-01/projects) |
| **Orchestration** | [test-ecommerce-suite-orchestration](https://github.com/mdizcalvinoaz400-01/test-ecommerce-suite-orchestration) |
| **Current Sprint** | Sprint 1 |

## 🛠️ Tech Stack

- **Cloud Provider:** AWS
- **IaC:** Terraform
- **Linting:** tflint
- **Department:** Infrastructure

## 🤖 Copilot Agents

| Agent | Purpose |
|-------|---------|
| `@terraform` | Terraform best practices |
| `@aws` | AWS resource patterns |
| `@security` | Security review |

## 📋 Commands

```bash
terraform init       # Initialize
terraform plan       # Preview changes
terraform apply      # Apply changes
terraform validate   # Validate config
tflint              # Lint
```

## 📁 Project Structure

```
terraform/
├── environments/    # Per-environment configs
│   ├── dev/
│   ├── staging/
│   └── prod/
├── modules/        # Reusable modules
└── shared/         # Shared resources
```

## 📖 Architecture

See `docs/architecture.md` for the high-level architecture document that guides infrastructure decisions.

## 🔗 Related Repositories

- [test-ecommerce-suite-orchestration](https://github.com/mdizcalvinoaz400-01/test-ecommerce-suite-orchestration) - Central coordination
- [test-ecommerce-suite-frontend](https://github.com/mdizcalvinoaz400-01/test-ecommerce-suite-frontend) - Frontend UI
- [test-ecommerce-suite-backend](https://github.com/mdizcalvinoaz400-01/test-ecommerce-suite-backend) - Backend API
