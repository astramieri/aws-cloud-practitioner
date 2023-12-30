# VPC & Networking Summary

- **VPC**: Virtual Private Cloud
- **Subnets**: Tied to a specific AZ, network partition of the VPC
- **Internet Gateway**: at the VPC level, provide internet access
- **NAT Gateway/Instances**: give internet access to private subnets
- **NACL**: Stateless, subnet rules for inbound and outbound
- **Security Groups**: Stateful, operate at the EC2 level or ENI
- **VPC Peering**: Connect two VPC with no overlapping IP ranges, nontransitive
- **Elastic IP**: fixed public IPv4, ongoing cost if not in-use
- **VPC Endpoints**: Provide private access to AWS services within VPC
- **PrivateLink**: privately connect to a service in a 3rd party VPC
- **VPC Flow Logs**: network traffic logs
- **Site to Site VPN**: VPN over public internet between on-premises data center and AWS 
- **Client VPN**: OpenVPN connection from your computer into your VPC
- **Direct Connect**: direct private connections to AWS
- **Transit Gateway**: connect thousands of VPC and on-premises networks together
