# Summary

- **VPC**: Virtual Private Cloud, tied to a specific region
- **Subnet**: network partition of the VPC, tied to a specific AZ
- **Internet Gateway**: at the VPC level, provide internet access
- **NAT Gateway/Instances**: give internet access to private subnets
- **NACLs**: stateless, subnet rules for inbound and outbound
- **Security Groups**: stateful, operate at the EC2 level or ENI
- **VPC Peering**: connect two VPC with no overlapping IP ranges, non-transitive
- **Elastic IP**: fixed public IPv4, ongoing cost if not in-use
- **VPC Endpoints**: provide private access to AWS services within VPC
- **PrivateLink**: privately connect to a service in a 3rd party VPC
- **VPC Flow Logs**: network traffic logs
- **Site to Site VPN**: VPN over public internet between on-premises data center and AWS 
- **Client VPN**: OpenVPN connection from your computer into your VPC
- **Direct Connect**: direct private connections to AWS
- **Transit Gateway**: connect thousands of VPC and on-premises networks together
