# CloudFormation
Deploying a CloudFormation Stack and various components on AWS.

# Project Components Include
o	Two VPCs, A and B.
o	Two Internet gateway attached to the respective VPCs.
o	Four subnets, two public, two privates.
o	The corresponding route tables for the public and private networks.
o	Two  security groups. The Public SG allows access to SSH and HTTP and to the VPC’s internal address   space. The Private SG only allows access to the VPC’s internal address space only.
o	Two webservers deployed on EC2 Instances with User Data boostrap.

