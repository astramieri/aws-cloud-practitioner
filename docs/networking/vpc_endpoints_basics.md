# VPC Endpoints Basics

- All the AWS services are **public**, when we connect to them, we are connecting to them publicly
- Endpoints allow you to connect AWS services using a private network instead of the public www network
- This gives you **enhanced security** and **lower latency** to access AWS services

Two types of VPC Endpoints:
- **VPC Endpoint Gateway**: S3 and DynamoDB
- **VPC Endpoint Interface**: the rest

![VPC Endpoints](../../images/networking/vpc_endpoints.png)

## AWS PrivateLink (VPC Endpoint Services)

- Most secure & scalable ways to expose a service to 1000s of VPCs
- Does not require VPC peering, Internet Gateway, NAT, route tables, etc.
- Requires a **Network Load Balancer** (3rd Service VPC)
- Requires an **Elastic Network Interface** (Customer VPC)
- All the internet traffic **do not go through the public internet**, but through your private network

![PrivateLink](../../images/networking/privatelink.png)