# Virtual Private Cloud
- logically isolated network in AWS
- control of network architecture 
- Enhanced Security
- VPC Peering - connect two VPC internetwork with other orgs
- Elastic IP addresses aka public IP addresses
- Enable hybrid cloud (site to site VPN)
- single tenant dedicated server hardware

# AWS Global Infrastructure 
- Networking Stack
- Compute Storage Database
- Application Services
- Deployment and Automation

# VPC elements
- Subnets (private public VPN) 
- route tables - traffic routing
- internet gateways (give access to internet)
- elastic IP addrese (pool of ip address)
- endpoints (aws services only available via internet can be avoided)
- NAT gateways  
- peering connections
- Network ACLs ( access control  lists)
- Security group
- VPN

# VPC Characteristics 
- AWS reserves 5 ip addresses per subnet(first 4 andd last 1) for mgmt purposes
- Private public or VPN subnets
- subnet donot span availability zones
- single region multiple availability zones
- CIDR block 16- 28
- Select IP prefix 

# VPC Security 
- Security groups 
