# Elastic Cloud Compute EC2
- launched in 2006
- instance to run applns
- remote machine or server 
- any kind of computing 
- Elastic means it can expand and retract as needed
- basic building block is instance - virtual server 
- launch instance 
* step 1 create image AMI
-- Operating system + software used on an ec2 instance
* step 2 Choose an instance type 
-- Different Instance types 
-- General purpose 
-- Memory optimized
-- Compute optimized
* Step 3 Cofigure instance types
-- auto scaling group 
-- number of instances that can auto scale
* Step 4 Add storage
-- Elastic Block Storage EBS used for EC2 file systems
* Step 5 -- Tag instances to add meta values for instance
* Step 6 Configure Security group

# Simple Storage Service S3
- store files 
- used by cloudwatch and elastic bean stalk
- Max size is 5 tb
## Bucket 
- root resource to add objects 
- configure to trigger events when objects are added
- preserve older versions of objects
- replicate objects across regions 
- s3 bucket url 
- https://s3-us-west region 
- /okfido.org bucket name
- / followed by path 
- hosting static website
### Use Cloudfront to cache your content
- edging your content

