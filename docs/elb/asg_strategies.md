# ASG Scaling Strategies

- **Manual Scaling**: update the size of an ASG manually
- **Dynamic Scaling**: responding to changing demand
    - Simple / Step Scaling
        - When a CloudWatch alarm is triggered (example CPU>70%) then add 2 units
        - When a CloudWatch alarm is triggered (example CPU<30%) then remove 1 unit
    - Target Tracking Scaling
        - Example: I want the average ASG CPU to stay around 40%
    - Scheduled Scaling
        - Anticipate a scaling based on known usage patterns
        - Example: increase the minimum capacity to 10 a 5 pm on Fridays 
- **Predictive Scaling**
    - Uses Machine Learning to predict future traffic ahead of time
        - Algorithms that looks at the past traffic patterns to forecast future traffic
    - Automatically provisions the right number of EC2 instances in advance
    - Useful when your load has predictable time-based patterns
