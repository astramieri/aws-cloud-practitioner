# ELB & ASG Summary

- **High Availability vs Scalability vs Elasticity vs Agility**
- **Elastic Load Balancers (ELB)**
    - Distribute traffic across backend EC2 instances, can be multi AZ
    - Supports health checks
    - 4 Types: 
        - Classic (old - retired 2023)
        - Application (lvl 7)
        - Network (lvl 4)
        - Gateway (lvl 3)
- **Auto Scaling Group (ASG)**
    - Implement Elasticity for you application across multiple AZ
    - Scale EC2 instances based on the demand on your system, replace unhealthy
    - Integrated with the ELB