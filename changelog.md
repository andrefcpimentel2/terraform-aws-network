## 1.0.3

NEW FEATURES:
* Added aws_ram_resource_share_accepter for the transit gateway attachment ([#15](https://github.com/zoitech/terraform-aws-network/issues/15))

## 1.0.2

IMPROVEMENTS:
* Removed public subnets from transit gateway vpc attachment ([#13](https://github.com/zoitech/terraform-aws-network/issues/13))

## 1.0.1

NEW FEATURES:
* DHCP Options (Optional) ([#9](https://github.com/zoitech/terraform-aws-network/issues/9))
* Internet Gateway (Optional)
* NAT Gateway (Optional) (Dependent on Internet Gateway)
* Elastic IP for NAT Gateway (Optional)
* Network ACL (Optional) ([#10](https://github.com/zoitech/terraform-aws-network/issues/10))
* Transit Gateway attachment to the VPC (Optional) ([#11](https://github.com/zoitech/terraform-aws-network/issues/11)))

BACKWARDS INCOMPATIBILITIES / NOTES:
* Works with terraform 0.12.x ([#8](https://github.com/zoitech/terraform-aws-network/issues/8))

IMPROVEMENTS:
* Upgraded to terrfaform 0.12 ([#8](https://github.com/zoitech/terraform-aws-network/issues/8))

BUG FIXES:
* Fixed output for nat gateway IP if not created ([#6](https://github.com/zoitech/terraform-aws-network/issues/6))