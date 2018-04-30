
### Limitations 
- Python 2.7
- Node.JS
- Java 8
- C#
- Size limitations  <25mb for microservices architecture
- Resource limitation  < 512mb
- max execution  <300secs 
- 100 concurrent lambda fns
- Memory 128mb to 1.5gb
- CPU scales with memory
- VPC Virtual Private Cloud access for lambda within the org

# Lambda Prerequisites 
- Building Lambda Canary fn
- Gather dependencies
 -- Libraries 
 -- Other files
 -- AWS services 
 -- API keys
 
 ## Writing Code 
 - zip all the code together as a function package
 - use logging stored in AWS cloudwatch
 - Env differences because the code runs on an amazon Linux machine 
 
 # Deploy Lambda / create function
 - Configure Cloudwatch schedule
 -- Select blueprint (sample configs of event sources and Lambda functions)
 -- Configure triggers
 -- Configure Function 
- environment variables 
- handler (code that thefn would call)
- VPC if required 
- encryption through the KMS key

# Monitoring and Alerting
## test event
- Configure test event 
- Enable trigger 
## Monitoring 
- invocations 
- duration
- errors
- Throttles
- cloudwatch log streaam
- Create Alarm for errors etc 

