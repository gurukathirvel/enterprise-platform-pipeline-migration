trigger:
  branches:
    include:
      - main

stages:
- stage: Validate
  jobs:
  - job: IaCScan
    steps:
    - script: tfsec .

- stage: Deploy
  dependsOn: Validate
  jobs:
  - deployment: DeployInfra
    environment: nonprod
    strategy:
      runOnce:
        deploy:
          steps:
          - script: terraform apply -auto-approve
