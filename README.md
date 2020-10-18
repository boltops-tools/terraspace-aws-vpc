# Terraspace AWS VPC Example

This project shows how to use the [AWS VPC Terraform registry module](https://registry.terraform.io/modules/terraform-aws-modules/vpc/aws) with [Terraspace](https://terraspace.cloud/).

* Thanks and credit goes to the author of this module: Anton B.
* Most contributors are doing this on their own free time. Please support them. Contribute back and send them a pull request. Some may ask for donations. Donate to them. Some are consultants. Hire them.

## Setup

    git clone https://github.com/boltops-tools/terraspace-aws-vpc
    cd terraspace-aws-vpc
    bundle

## Deploy

To deploy:

    terraspace up simple-vpc

Note, the vpc deploys to the `eu-west-1` region.

## Updating

To update the modules to the latest version from the Terraform registry.

    terraspace bundle update

## More Examples

    $ terraspace list
    app/stacks/complete-vpc
    app/stacks/ipv6
    app/stacks/issue-108-route-already-exists
    app/stacks/issue-44-asymmetric-private-subnets
    app/stacks/issue-46-no-private-subnets
    app/stacks/manage-default-vpc
    app/stacks/network-acls
    app/stacks/secondary-cidr-blocks
    app/stacks/simple-vpc
    app/stacks/vpc-flow-logs
    app/stacks/vpc-separate-private-route-tables

## About

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

[Terraspace](https://terraspace.cloud/) and this project was built by [BoltOps](https://www.boltops.com). We also offer:

* [Paid Consulting Services](https://www.boltops.com/consulting)
* [BoltOps Pro: Infrastructure Code as a Service](https://www.boltops.com/pro)
