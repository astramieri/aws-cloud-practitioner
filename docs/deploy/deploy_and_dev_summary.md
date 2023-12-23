# Deployment and Developer Summary

## Deployment

- **CloudFormation** (AWS only)
    - Infrastructure-as-a-Code (IaaC), 
    - Works with almost all of AWS resources
- **Beanstalk** (AWS only)
    - Platform-as-a-Service (PaaS)
    - Limited to certain programming language or Docker
    - Deploy code consistently with a known architecture (e.g. ALB + EC2 + RDS)
- **CodeDeploy** (hybrid)
    - deploy and upgrade any application onto servers
    - EC2 instances or on-premises infrastructure
- **System Manager** (hybrid)
    - patch, configure and run commands at scale
- **OpsWorks**
    - managed Chef and Puppet in AWS

## Development

- **CodeCommit**
    - Store code in private Git repository (version controlled)
- **CodeBuild**
    - Build and test code in AWS
- **CodeDeploy**
    - Deploy code onto servers
- **CodePipeline**
    - Orchestration of pipeline (from code to build to deploy)
- **CodeArtifact**
    - Store software packages / dependecies on AWS
- **CodeStart**
    - Unified view fro allowing developers to do CICD and code
- **Cloud9**
    - Cloud IDE (Integrated Development Environment) with collaboration features
- **AWS CDK**
    - Define your cloud infrastructure using a programming language (compiled into a CloudFormation template)