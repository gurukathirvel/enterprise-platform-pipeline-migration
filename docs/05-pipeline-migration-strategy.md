# CI/CD Pipeline Migration Strategy

## Objective
Migrate legacy UI-based pipelines to YAML-based pipelines with improved
security, traceability, and reuse.

## Migration Phases
1. Assess existing pipelines
2. Convert to YAML definitions
3. Introduce reusable templates
4. Add security scanning stages
5. Enforce approvals via environments

## Before vs After

| Area | Legacy | Target |

| Definition | UI | YAML in Git |
| Versioning | None | Git-based |
| Security | Manual | Automated |
| Approvals | Informal | Policy-driven |

## Tooling
- Azure DevOps YAML pipelines
- GitHub Actions
- Artifact repositories
