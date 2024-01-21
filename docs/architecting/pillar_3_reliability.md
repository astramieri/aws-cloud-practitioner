# AWS Well-Architected Framework - Pillar 3: Reliability

- Ability of a system to recover from infrastructure or service disruptions, dynamically acquire computing resources to meet demand, and mitigate disruptions such as misconfigurations or transient network issues
- Design Principles
    - **Test recovery procedures**
        - Use automation to simulate different failures or to recreate scenarios that led to a failure before
    - **Automatically recover from failure**
        - Anticipate and remediate failures before they occur
    - **Scale horizontal to icnrease aggregate system availability**
        - Distribute requests accross multiple, smaller resources to ensure that they don't share a common point of failure
    - **Stop guessing capacity**
        - Maintain the optimal level to satisfy demand without over or under provisioning
        - Use auto scaling
    - **Manage change in automation**
        - Use automation to make changes to infrastructure

## Reliability - AWS Services

- Foundations
    - IAM
    - AWS VPC
    - AWS Service Quotas (prior *Service Limits*)
    - AWS Trusted Advisor
- Change Management
    - AWS Auto Scaling
    - AWS CloudWatch
    - AWS CloudTrail
    - AWS Config
- Failure Management
    - AWS Backups
    - AWS CloudFormation
    - AWS S3
    - AWS Route 53