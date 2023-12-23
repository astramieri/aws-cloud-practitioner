# Global Application

A **global application** is an application deployed in **multiple geographies**. In AWS this means in multiple **regions** and/or **edge locations**.

Global Application Use Cases:
- **Decreased Latency**
    - Latency is the time it takes for a netowrk packet to reach the server
    - Deploy the application closer to you users for better experience
- **Disaster Recovery (DR)**
    - If an AWS region goes down (earthquake, storms, power shutdown, politics, etc.)
    - You can fail-over to another region and have your application still working
    - A DR plan is important to increase the availability of your application
- **Attack Protection**
    - Distributed global infrastructure is harder to attack

## Global AWS Infrastructure

- **Regions**: for deploy application and infrastructure
- **Availability Zones**: made of multiple data centers
- **Edge Locations** (Points of Presence): for content delivery as close as possibile to users

## Global Application in AWS

- Global DNS: **Ruote 53**
    - Great to route users to the closest deployment with last latency
    - Great for disaster recover strategy
- Global Content Delivery Network (CDN): **CloudFront**
    - Replicate part of your application to AWS Edge Locations (decrease latency)
    - Cache common requests (improved user experience and decreased latency)
- **S3 Transfer Acceleration**
    - Accelerate global upload & donwloads into Amazon S3
- **AWS Global Accelerator**
    - Improve global application availability and performance using the AWS global network