# Summary

- **EC2 Instance Store**
    - High performance hardware disk attached to our EC2 instance
    - Lost if our instance is stopped / terminated
- **EBS Volumes**
    - Network drives attached to one EC2 instance at a time
    - Mapped to an AZ
    - Can use EBS snapshots for backups/trasferring EBS volumes across AZ
- **EFS**
    - Network file system
    - Can be attached to hundreds of instances in a region
- **EFS-IA**
    - Cost-optimized storage class fro infrequent accessed files
- **FSx for Windows**
    - Network file system for windows servers
- **FSx for Lustre**
    - High performance computing linux file system