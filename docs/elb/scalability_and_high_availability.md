# Scalability and High Availability

## Scalability

Scalability means that an application or system can handle greater loads by adapting.

The are two kinds of scalability:
- vertical scalability
    - it means increasing the size of the instance/system
        - e.g. from *t2.micro* to *t2.large*
    - it is very common for non distributed system (e.g. database)
    - there is usually a limit to how much you can scale (hardware limit)
- horizontal scalability (= elasticity)
    - it means increasing the number of instances/systems for you application
    - horizontal scaling implies distributed systems
    - this is very common for web/modern application

Scalability is linked but different to High Availability.

## High Availability

High Availability usually goes hand in hand with horizontal scaling.

High Availability means running your application/system in at least 2 Availability Zones.

The goal of high availability is to survive a data center loss (disaster).

## Scalability and High Availability for EC2

- Vertical Scaling: increase instance size (= scale up/down)
    - from t2.nano (0.5 GB of RAM, 1 vCPU)
    - from u-12tb1.metal (12.3 TB of RAM, 448 vCPUs)

- Horizontal Scaling: increase numbner of instances (= scale in/out)
    - Auto Scaling Group
    - Load Balancer

- High Availability: run instances for the same application across multi AZ
    - Auto Scaling Group multi AZ
    - Load Balancer multi AZ

## Scalability vs Elasticity vs Agility

**Scalability** is the ability to accomodate a larger load by making the hardware stronger (scale up) or by adding nodes (scale out).

**Elasticity** means that there will be some **auto-scaling** so that the system can scale based on the load. This is *cloud-friendly*: pay-per-use, match demand, optimize costs.

**Agility** (not related to scalability - distractor) means that new IT resources are only a *click-away* which means that you reduce the time to male those resources available to your developers from weeks to just minutes.