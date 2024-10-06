# NT548-lab1-group9-CloudFormation
NT548-lab1-group9-CloudFormation
STEP:
- Clone
- aws configure
- aws s3 cp [Name of modules].yml s3://cloudformation-modules
- aws cloudformation delete-stack --stack-name [Name of Stack]
- aws cloudformation create-stack --template-body file://[URL to the sample file in your PC] --stack-name [Name of Stack]
