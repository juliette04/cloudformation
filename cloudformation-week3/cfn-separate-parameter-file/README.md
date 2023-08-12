## AWS CLI Commands
https://docs.aws.amazon.com/cli/latest/index.html

## Validate Cloudformation template
aws cloudformation validate-template --template-body file://nextgen-network-infra.yaml
--parameters file://nextgen-network-infra-parameter-file.json

## create cloudformation stack
aws cloudformation create-stack --stack-name myteststack --template-body file://nextgen-network-infra.yaml --parameters file://nextgen-network-infra-parameter-file.json