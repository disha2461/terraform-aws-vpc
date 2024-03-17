### VPC

This module is going to create

* vpc
* Internet gateway
* 2-public subnets
* 2-private subnets
* 2- Database subnets

### Inputs

* cidr_block(requried) - user has to provide cidr_block
* enable_dns_hostnames(optional) - user can provide enable_dns_hostnames
* enable_dns_support(optional) - user can provide enable_dns_support
* common_tags(optional) - user can provide commontags for all resources, default is empty
* vpc_tags(Optional) - user can provide vpc tags for vpc resources.
*igw_tags(optional) - user can provide igw tags for internet gateway.
* public_subnet_cidr(required) - user must provid a list of 2 public subnet CIDR
* public_subnet_names - user must provid a list of 2 public subnet names
* azs - user must provid a list of 2 azs