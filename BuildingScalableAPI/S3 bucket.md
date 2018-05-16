# Create s3 bucket
- Select a bucket name and region
- choose the bucket that is created and actions menu upload
- Create lambda fn with handler and role 
- under actions menu configure sample events
- Test to see output of the function

- Create Resource and choose the POST method verb
- choose lambda as the integration type and select the region 

# Adding url parameters 
## Mapping templates
- allows to map or transform our data
e.g - url to json object 
- In API gateway a mapping template is used to transform data from one format to another
### Mapping template variables 
#### Context 
- holds all the contextual information for your API
- $context.apiId
- $context.identity.accountOwner
- $context.identity.sourceIp
- $context.identity.userAgent

#### Input
- represents the imput payload and Parameters to be processed by templates
- $input.json (x)
- $input.params ()
- $input.path (x)

#### Util 
- collection of utility fns for mapping templates
- $util.escapeJavaScript
- $util.urlEncode / decode 
- $util.base64Encode
