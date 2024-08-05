# CD12352 - Infrastructure as Code Project Solution
# QuynhLTD

## Spin up instructions
Create stack:
aws cloudformation update-stack --stack-name udagram-stack --template-body file://udagram.yml  --parameters file://params.json --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM" --region=us-east-1

## Tear down instructions
aws cloudformation delete-stack --stack-name udagram-stack --region=us-east-1

## URL
http://udagramwebapp-665928056.us-east-1.elb.amazonaws.com