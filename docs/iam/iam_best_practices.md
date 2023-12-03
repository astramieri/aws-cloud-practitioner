# IAM Best Practices

Guidelines & Best Practices
- do not use the root account except for AWS account setup
- one physical user = one AWS user
- assign users to groups and assign permissions to groups
- create a strong password policy
- use and enforce the use of multi factor authentication (MFA)
- create and use roles for giving permissions to AWS services
- use access keys for programmatic access (CLI/SDK)
- audit permissions of your account using IAM Credentials Report & IAM Access Advisor
- **never share IAM users & access keys**