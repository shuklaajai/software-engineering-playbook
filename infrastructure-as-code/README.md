# 🏗️ Infrastructure as Code

Terraform configurations, modules, and best practices.

## 📚 Topics Covered

- **Terraform Basics** - State management, providers, resources
- **Modules** - Creating reusable infrastructure components
- **AWS Resources** - EC2, RDS, VPC, IAM, Lambda
- **Best Practices** - DRY, versioning, testing, linting
- **Advanced Topics** - Workspaces, remote state, automation
- **Kubernetes** - Managing Kubernetes with Terraform
- **Git Integration** - Version control for infrastructure

## 📂 Structure

```
infrastructure-as-code/
├── README.md
├── tutorials/
│   ├── terraform-fundamentals/
│   ├── aws-with-terraform/
│   ├── kubernetes-terraform/
│   ├── terraform-modules/
│   └── ...
├── projects/
│   ├── vpc-setup/
│   ├── kubernetes-cluster/
│   ├── complete-aws-infrastructure/
│   └── ...
├── templates/
│   ├── modules/
│   │   ├── vpc/
│   │   ├── rds/
│   │   ├── eks/
│   │   └── ...
│   ├── environments/
│   │   ├── dev/
│   │   ├── staging/
│   │   └── prod/
│   └── ...
└── notes/
    ├── terraform-cheatsheet.md
    ├── state-management.md
    └── ...
```

## 🎯 Learning Path

### Beginner
1. Terraform syntax & basics
2. State management
3. Basic AWS resources
4. Variables & outputs

### Intermediate
1. Module creation & reuse
2. Multiple environments
3. Remote state
4. Best practices

### Advanced
1. Custom providers
2. Advanced module patterns
3. Testing infrastructure code
4. GitOps workflows

## 🚀 Quick Start

```bash
# Start with fundamentals
cd tutorials/terraform-fundamentals/
cat README.md

# Learn AWS-specific patterns
cd ../aws-with-terraform/

# Reference a complete project
cd ../../projects/complete-aws-infrastructure/
```

## 📖 Key Resources

- Terraform Official Documentation
- Terraform Registry (modules)
- AWS Provider Documentation
- Community best practices

## 💡 Pro Tips

✅ Use remote state (S3 + DynamoDB)  
✅ Organize with modules  
✅ Separate environments clearly  
✅ Version your modules  
✅ Test with terraform plan first  

## 🔗 Cross-Domain Learning

- **Cloud Infrastructure**: Deploy AWS resources
- **Container Orchestration**: Provision Kubernetes
- **DevOps/SRE**: Automate infrastructure changes
- **Observability**: Monitor infrastructure