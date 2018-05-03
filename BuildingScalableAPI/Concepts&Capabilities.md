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

## Throttling API calls
- throttle by burst
- throttle by rate limits 
- This helps us prevent overloading backend services 
- Requests over the limit receive HTTP 429 response 
- Defined at the stage
- Can be overwritten at the method level

## Caching your API requests
- Configured per stage
- Improve performance 
- reduce traffic
- from0.5gb to to 237GB cache
- charged seperatly for the cache

### Billing
- $3.5 per million API requests 
- Data out charges -- $0.09 for first 10 TB
-- $0.085 for next 40TB
-- $0.07 for next 100 TB
-- $0.05 for next 350 TB
- Cache charges
-- from  $0.02 to $3.80 upto 237GB


