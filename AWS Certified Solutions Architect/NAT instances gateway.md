# Network Address Translation Gateway 
- connect private to public network

## NAT instances vs NAT gateway
- NAT instances
-- use a script to manage failover between instances
-- depends on bandwidth of instance type
-- managed by you
-- generic Amazon linux AMI thats configured to perform NAT
-- Manual Port forwarding 
-- cloudwatch alarms
- NAT gateway 
-- highly avail ,implemented with redundancy 
-- supports burst of upto 10 Gbps
-- managed by AWS
-- software optimized for handling NAT traffic
-- Port forwarding supported 

### NAT gateway in action
- In EC2 -> launch instances -> Community AMIs -> search NAT
- In VPC -> Nat gateway and associations 
