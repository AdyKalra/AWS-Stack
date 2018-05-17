### Purpose of an API key
- monitoring and usage of the API
- writes to cloudwatch logs
- per method level
- not for authorization!
- use signedAPI calls or oAuth authorization instead

## Setting up our API key
- create API keyfrom dashnoard
- which stage 
- authorization type
- IAM role 

# Creating API key 
- Name 
- Description 
- enabled 
- stages its used for 

## Associating the API key with resources 
- Adding x-api key header helps in requesting the API
- without theheader it would return a 403
- create policy statement for api gateway 
- IAM role for the api gateway 
- view cloudwatch logs 

