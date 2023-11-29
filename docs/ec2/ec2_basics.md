## EC2 Basics

Elastic Compute Cloud (EC2) is one of the most popular of AWS offering.

EC2 is not just one service, it mainly consists:
- renting virtual machine (EC2 instances)
- storing data on virtual drives (EBS volumes)
- distributing load across machine (ELB - Elastic Load Balancer)
- scaling services using an auto-scaling group (ASG)

## EC2 Sizing & Configuration Options

- Operating System (OS): Linux, Windows, Mac OS
- Computer power & cores (CPU)
- Random access memory (RAM)
- Storage space
    - Network-attached (EBS & EFS)
    - Hardware-attached (EC2 Instance Store)
- Network card: speed of the card, public ip address
- Firewall rules: security group
- Boostrap script (configure at first launch): EC2 User Data

## EC2 User Data

It is possible to bootstrap our instance using an **EC2 user data script**. 

This script **only run once** ad the instance **first start**. 

The EC2 User Data Script runs with the root user.

EC2 user data is used to automate boot tasks such as:
- installing updates
- installing software
- downloading common files from the internet
- *anything you can think of*

EC2 instance type: **t3.micro** is part of the AWS free tier (up to 750 hours per month)
