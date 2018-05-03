- Create Restful API that call publicly available http endpoints
- Lambda fns that we have created
- call any avail services

# What is a REST API?
- endpoints = a group if resources and methods 
e.g POST endpoint
- can be versioned

## Http verbs supported by each resource 
- DELETE
- GET
- HEAD
- OPTIONS
- PATCH
- POST
- PUT

## Definition of a Stage
- similar to tags tgat define the accessible path
-- https://myapi.com/dev/shoes
-- https://myapi.com/beta/shoes
-- https://myapi.com/v1/shoes
- dev beta v1 are diff stages of the same API

### Lifecycle of an API
- API -> Staging -> prod v1 v2 and so on

## API monitoring 
- Cloudwatch
- API calls latency and errors
- set up alarms based on trigger 
- Logs can be filtered based on Version Method 

## Use of Https
- All calls are done via https
- default API use AWS SSL certificate 
- you can also use custom SSL certificate 

## Using API Gateway with VPC
- All AWS APIs are publicly accesible
- Cannot communicate with services inside a VPC umless a public endpoint is exposed 
- e.g If we have API on public internet and an EC2 instance inside our VPC 
-- add an elastic IP to the EC2 instance redirect the API to the service




