# AWS Budgets

- Create budget and **send alarms when costs exceeds the budget**
- 4 types of budgets:
    - Usage
    - Cost
    - Reservation
    - Saving Plans
- For Reserved Instances (RI)
    - Track utilization
    - Supports EC2, ElastiCache, RDS, Redshift
- Up to 5 SNS notifications per budget
- Can be filter by:
    - Service
    - Linked Account
    - Tag
    - Purchase Option
    - Instance Type
    - Region
    - Availability Zone,
    - API Operation
    - etc.
- Same options as AWS Cost Explorer
- **2 budgets are free, then $ 0.02/daybudget**

## CloudWatch Billing Alarms vs Budgets

CloudWatch Billing Alarms only send alerts when your costs and usage are exceeding your budget, **not when it is forecasted** to exceed your budget, while AWS Budgets does both.