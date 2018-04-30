<b>Update Function Code</b>
<p>It updates the code of the desired Lambda function</p>
<p>Syntax</p>

      update-function-code
    --function-name <value>
    [--zip-file <value>]
    [--s3-bucket <value>]
    [--s3-key <value>]
    [--s3-object-version <value>]
    [--publish | --no-publish]
    [--dry-run | --no-dry-run]
    [--cli-input-json <value>]
    [--generate-cli-skeleton <value>]
<p>Example</p>

    update-function-code --function-name functionName
<br>
<b>Update Function Configuration</b>
<p>It updates the configuration of the desired Lambda function</p>
<p>Syntax</p>

      update-function-configuration
    --function-name <value>
    [--role <value>]
    [--handler <value>]
    [--description <value>]
    [--timeout <value>]
    [--memory-size <value>]
    [--vpc-config <value>]
    [--environment <value>]
    [--runtime <value>]
    [--dead-letter-config <value>]
    [--kms-key-arn <value>]
    [--tracing-config <value>]
    [--cli-input-json <value>]
    [--generate-cli-skeleton <value>]
<p>Example</p>

    update-function-configuration --function-name functionName
<br>
<h4>References</h4>
<ul>
  <li><a href="https://aws.amazon.com/documentation/lambda/">AWS Lambda Docs</a></li>
  <li><a href="https://boto3.readthedocs.io/en/latest/">Boto 3 Docs</a></li>
  <li><a href="http://docs.aws.amazon.com/cli/latest/reference/lambda/">AWS CLI Docs</a></li>
  <li><a href="http://docs.sqlalchemy.org">SQLAlchemy Docs</a></li>
</ul>
<br>
<b>For queries or issues, feel free to contact or open an <a href="https://github.com/srcecde/aws-lambda-cheatsheet/issues">issue</a></b>
