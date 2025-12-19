# Enterprise Platform & CI/CD Pipeline Migration Reference Architecture

## Objective
This repository demonstrates an enterprise-grade platform engineering approach
to designing cloud infrastructure and migrating CI/CD pipelines from legacy,
UI-driven implementations to modern, secure, and scalable YAML-based pipelines.

The focus is on:
- Platform architecture (AWS & Azure)
- CI/CD pipeline migration strategy
- Security-by-design and governance
- Operational excellence

## Scope
- Multi-account / multi-subscription cloud platform design
- Infrastructure as Code using Terraform
- CI/CD migration (Classic → YAML → GitHub Actions)
- Security scanning and policy enforcement
- Hybrid connectivity (on-prem to cloud)

## Assumptions
- Regulated enterprise environment
- Multiple delivery teams consuming the platform
- Shared responsibility between platform and application teams

## High-Level Architecture
Refer to `architecture/diagrams/target-state.drawio`

## Design Principles
- Infrastructure as Code first
- Least privilege and zero trust
- Shift-left security
- Platform as a product
- Automation over manual controls


