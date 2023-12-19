# Elastic Beanstalk

This architecture is something we can easily reproduce manually or with CloudFormation, but there is a better way.

![Typical Wep App 3-tier Architecture](../../images/deploy/web_app_3_tier.png)

Developer problems on AWS:

- managing infrastructure
- deploying code
- scaling concerns

## Elastic Beanstalk Overview

- Elastic Beanstalk is a **developer centric** view of deploying an application on AWS
- We still have full control over the configuration
- **Beanstalk = Platform as a Service (PaaS)**
- Beanstalk is free but you pay for the underlying instances
- Beanstalk is a **managed service**
    - Instance configuration/OS is handled by Beanstalk
    - Deployment strategy is configurable but performed by Beanstalk
    - Capacity provisioning
    - Load balancing & auto-scaling
    - Application health-monitoring & responsiveness
- Three architecture models:
    - Single Instance deployment (good for dev)
    - LB + ASG: great for production or pre-production web applications
    - ASG only: great for non-web apps in productions (workers, etc.)
- Support for many platforms
    - Go, Java, PHP, Python, etc.
    - Single/Multi/Pre-configured Docker
    - If not supported, you can write your custom platform! (advanced)

## Health Monitoring

Beanstalk has a full monitoring suite available within the service itself. 

Health agent pushes metrics to CloudWatch.



