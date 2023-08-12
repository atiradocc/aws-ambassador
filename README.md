# aws-ambassador

Just a place to put a couple of AWS CloudFormation templates for reference

- `simpleEC2Instance.template.yaml` - creates an EC2 instance but assumes a keypair called `AWSAmbassadorKeypair` is available
- `simpleEC2Instancewithkeypair.template.yaml` - creates an EC2 instance and its own keypair. Note: The private key will be avaialble in AWS SSM Parameter Store
