# CD12352 - Infrastructure as Code Project Solution
# QuynhLTD

## Spin up instructions
aws cloudformation update-stack --stack-name udagram-stack --template-body file://udagram.yml  --parameters file://params.json --capabilities "CAPABILITY_IAM" "CAPABILITY_NAMED_IAM" --region=us-east-1

## Tear down instructions
Link
http://UdagramWebApp-1470370328.us-east-1.elb.amazonaws.com
