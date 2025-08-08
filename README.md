aws cloudformation deploy \
  --stack-name vpc-dev-prod-peering \
  --template-file ./vpc-peering-dev-prod.yml \
  --capabilities CAPABILITY_NAMED_IAM
