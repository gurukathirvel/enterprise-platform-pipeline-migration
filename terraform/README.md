# Terraform Structure

## Modules
Reusable building blocks for:
- Networking
- Kubernetes
- IAM
- Logging
- Security controls

## Environments
- dev
- nonprod
- prod

Each environment consumes the same modules with different inputs.

## Best Practices
- Remote state
- State locking
- Versioned modules
- Explicit provider configuration
