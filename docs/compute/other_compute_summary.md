# Other Compute Summary

- **Docker**: container technology to run applications
- **ECS**: run Docker containers on EC2 instances
- **Fargate**: run Docker containers serverless
- **ECR**: private docker images repository
- **Batch**: run batch jobs on AWS across managed EC2 intances
- **Lightsail**: predictable & low pricing for simple applications & DB stacks

# Lamba Summary

- Lambda is serverless, Function as a Service, seamless scaling, reactive
- Lambda billing:
    - by the time run x by the RAM provisioned
    - by the number of invocations
- Language support: many programming language except (arbitrary) Docker
- Invocation time: up to 15 minutes
- Use cases:
    - create thumbnails for images uploaded onto S3
    - run a serverless CRON job
- API Gateway: expose Lambda functions as HTTP APIs
