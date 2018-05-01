## Amazon SES (Simple email service)
- high deliverability
- sender statistics 
- control flow
- Monitoring 

- Verify all your email address in SES console
- test email

## S3 (Simple storage Service)
- Object storage
- buckets to hold objects
- Global namespaces
- Managed by AWS

- aws s3api create-bucket
- region us-east-1

### Python libraries 
- AWS SDK boto3
- HTML template Jinja2

## Testing your Lambda fn
- Cuckoo handler and pass context values

## Function package setup
- Open setup.sh
-- create virtual env 
-- create setup dir
-- move relevant files in setup dir
-- install requirements
-- prepare deployment package Zipping package.zip

- bash setup.sh

# Function deployment and config with AWS command line 
- aws iam list-roles
- find arn value from the role
- aws lambda create function 
- refresh aws lambda console to see the lambda fn
