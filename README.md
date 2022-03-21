# CloudFormation
Deploying a CloudFormation Stack and various components on AWS.

# Project Components Include
- Two VPCs, A and B.
- Two Internet gateway attached to the respective VPCs.
- Four subnets, two public, two privates.
- The corresponding route tables for the public and private networks.
- Two  security groups. The Public SG allows access to SSH and HTTP and to the VPC’s internal address   space. The Private SG only allows access to the VPC’s internal address space only.
- Two webservers deployed on EC2 Instances with User Data boostrap.

