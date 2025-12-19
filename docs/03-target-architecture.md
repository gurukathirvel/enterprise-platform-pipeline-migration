# Target Architecture

## Architecture Overview
The target architecture follows a hub-and-spoke / landing zone model
with strong separation of concerns.

## AWS
- Management account
- Shared services account
- Workload accounts (per environment)
- Centralized logging and security

## Azure
- Management groups
- Shared platform subscription
- Environment-specific subscriptions

## Key Components
- Kubernetes (EKS / AKS)
- Serverless (Lambda)
- API Gateway
- Centralized IAM / RBAC
- Observability stack

## Outcomes
- Strong isolation between workloads
- Consistent security controls
- Scalable platform growth
