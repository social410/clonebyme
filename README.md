# Repo: cfn-vpc
# AWS Cloudformation Stack Creation Templates for various VPC Creation scenarios.
# - Replace ALL 'ProjectName' with your Project Name, or customize resource(s) names as per requirement.
# - Create Stack in AWS Cloudformation by importing file or as s3 object.

# cfn_VPC_Template_1.yml
- Creates AWS Components like VPC, Public/Private Subnets, SG, Internet Gateway with attached Public Route.
- Create EC2 Instance in PublicSubnet with PublicIP OR Create & attach EIP to connect your instance remotely using Pubic IP.
