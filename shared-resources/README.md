# 🔧 Shared Resources

Common templates, utilities, and configurations shared across all skill domains.

## 📂 Contents

```
shared-resources/
├── README.md
├── config-templates/
│   ├── .env.example
│   ├── .env.production
│   ├── docker-compose-base.yml
│   └── ...
├── code-templates/
│   ├── api-client/
│   ├── database-connection/
│   ├── logging-setup/
│   └── ...
├── documentation-templates/
│   ├── README-template.md
│   ├── API-docs-template.md
│   ├── DESIGN-DOC-template.md
│   └── ...
├── scripts/
│   ├── setup.sh
│   ├── deploy.sh
│   ├── backup.sh
│   └── ...
└── utils/
    ├── logging/
    ├── validation/
    ├── error-handling/
    └── ...
```

## 📚 Available Templates

### Configuration Templates
- Environment file templates
- Docker Compose base setup
- Docker base configurations
- Kubernetes YAML templates

### Code Templates
- API client setup
- Database connection patterns
- Logging configuration
- Error handling wrappers

### Documentation Templates
- README template
- API documentation
- Design document template
- Architecture decision records

### Scripts
- Setup scripts
- Deployment scripts
- Backup & recovery
- Monitoring scripts

### Utilities
- Logging utilities
- Input validation
- Error handling
- Data formatting

## 🚀 How to Use

### Copy a Template
```bash
# Copy to your project
cp -r shared-resources/code-templates/api-client/ your-project/

# Or reference directly
cat shared-resources/templates/README-template.md
```

### Use as Reference
```bash
# View available utilities
ls -la shared-resources/utils/

# Reference a pattern
cat shared-resources/utils/logging/setup.py
```

## 💡 Contributing

When you find useful patterns:
1. Extract to a template
2. Add to shared-resources
3. Document usage
4. Update this README

## 🔗 Cross-Domain Usage

These templates are used by:
- Mobile Development
- Container Orchestration
- Cloud Infrastructure
- DevOps/SRE
- AI/ML projects
- Data Science

## ✅ Best Practices

✅ Keep templates generic  
✅ Document assumptions  
✅ Include examples  
✅ Version templates  
✅ Update regularly