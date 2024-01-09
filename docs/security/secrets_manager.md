# AWS Secrets Manager

- **AWS Secrets Manager** is a newer kind of service and it is meant for storing secrets (e.g. passwords)
- Capability to force rotation of secrets every N days
    - E.g. "every 90 days I want to change my password"
- Automate generation of secrets on rotation (uses Lambda)
- Integration with Amazon RDS (MySQL, PostreSQL, Aurora)
    - You can create the password for RDS automatically
- Secrets are encrypted using KMS