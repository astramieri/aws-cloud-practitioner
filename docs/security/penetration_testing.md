# Penetration Testing

- AWS customers are welcome to carry out security assessments or penetration test against their AWS infrastructure **without prior approval** for 8 services:
    - EC2 instances, NAT Gateways and ELB
    - RDS
    - CloudFront
    - Aurora
    - API Gateways
    - Lambda & Lamba Edge functions
    - Lightsail resources
    - Elastic Beanstalk environments
    - (List can increase over time)
- **Prohibited Activities**:
    - DNS zone walking via Amazon Route 53 Hosted Zones
    - Denial of Service (DoS) or Simulated DoS
    - Distributed Denial of Service (DDoS) or Simulated DDoS
    - Port flooding
    - Protocol flooding
    - Request flooding (login request flooding, API request flooding)