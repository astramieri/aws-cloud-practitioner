# VPC Basics

VPC stands for **Virtual Private Cloud**.

## IP Addresses in AWS

- **IPv4: Internet Protocol version 4** (4.3 Billion addresses)
    - **Public IPv4** can be used on the Internet
        - EC2 instance gets a new a public IP address every time you stop then start it (default)
    - **Private IPv4** can be used on private networks (LAN) such as internal ASW networking (e.g. 192.168.1.1)
        - Private IPv4 is fixed for EC2 instaces even if you start/stop them
- **Elastic IP**: allows you to attach a fixed public IPv4 address to EC2 instance (it will cost you!)
    - **Note**: has ongoing cost if not attached to EC2 instance or if the EC2 instance is stopped (because AWS needs to pay to keep that public IP alive and within its own network.)
- **IPv6: Internet Protocol version 6** (3.4 x 10^38 addresses)
    - **Every IP address is public (no private range)**
    - Example: 2001:db8:3333:4444:cccc:dddd:eeee:ffff
