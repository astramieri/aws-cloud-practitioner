# AWS Config

- **AWS Config** is a per-region service to help with **auditing and recording compliance** of your AWS resources
- It helps **record configurations and changes over time** 
- Possibility of storing the configuration data into S3 (analyzed by Athena)
- Question that can be solved by using AWS Config:
    - Is there unrestricted SSH access to my security groups?
    - Do my buckets have any public access?
    - How has my ALB configuration changed over time?
- You can receive alerts (SNS notifications) for any changes
- You can aggregate multiple AWS Config configuration across regions and accounts

