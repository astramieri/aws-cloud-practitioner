# EC2 Storage Summary

- **EBS volumes**
    - network drives attached to one EC2 instance at a time
    - mapped to an availability zone
    - can use EBS snapshots for backups/trasferring EBS volumes across AZ
- **EC2 Instance Store**
    - high performance hardware disk attached to our EC2 instance
    - lost if our instance is stopped / terminated
- **EFS**
    - network file system
    - can be attached to hundreds of instances in a region
- **EFS-IA**
    - cost-optimized storage class fro infrequent accessed files
- **FSx for Windows**
    - network file system for windows servers
- **FSx for Lustre**
    - high performance computing linux file system