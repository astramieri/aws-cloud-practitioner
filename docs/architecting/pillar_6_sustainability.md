# AWS Well Architected Framework - Pillar 6: Sustainability

- Focuses on minimizing the environmental impacts of running cloud workloads
- Design Principles
    - **Understand your impact**
        - Establish performance indicators
        - Evaluate improvements
    - **Establish sustainability goals**
        - Set long-term goals for each workload, model return on investment (ROI)
    - **Maximize Utilization**
        - Right size each workload to maximize the energy efficiency of the underlying hardware and minimize idle resources
    - **Anticipate and adopt new, more efficient hardware and software offering**
        - Design for flexibility to adopt new technologies over time
    - **Use managed services**
        - Shared services reduce the amount of infrastructure
        - Managed services help automate sustainability best practices as moving infrequent accessed data to cold storage and adjusting computing capacity
    - **Reduce the downstream impact of your cloud workloads**
        - Reduce the amount of energy or resources required to use your services and reduce the need for your customers to upgrade their devices

## Sustainability - AWS Services

- EC2 Auto Scaling
- Serverless Offering (Lambda, Fargate)
- Cost Explorer 
- EC2 Graviton 2, EC2 T instances, EC2 Spot Instances
- EFS-IA, S3 Glacier, EBS Cold HDD Volumes
- S3 Lifecycle Configuration, S3 Intelligent Tiering
- Data LyfeCicle Manager
- Read Local, Write Global: RDS Replicas, Aurora Global DB, DynamoDB Global Table, CloudFront