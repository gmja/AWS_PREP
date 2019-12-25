![](https://user-images.githubusercontent.com/26511983/70856789-aaf8ea00-1ea8-11ea-8a4d-d26e81c18016.png)

![](https://user-images.githubusercontent.com/26511983/71448911-b9e16700-2708-11ea-982d-70c156959691.png)

![](https://user-images.githubusercontent.com/26511983/71448990-2741c780-270a-11ea-8955-bfbd1a96ddbd.png)

![](https://user-images.githubusercontent.com/26511983/71449110-037f8100-270c-11ea-96f0-9b23426d5a8d.png)

![](https://user-images.githubusercontent.com/26511983/71449167-16df1c00-270d-11ea-95e5-4eda20becdec.png)

![](https://user-images.githubusercontent.com/26511983/71449169-370edb00-270d-11ea-97df-c1cfd2bfc8e9.png)

![](https://user-images.githubusercontent.com/26511983/71449176-645b8900-270d-11ea-82c4-c98734360e7e.png)

![](https://user-images.githubusercontent.com/26511983/71449220-2b6fe400-270e-11ea-890d-981800df4a01.png)

#
## The initially-assigned IPv4 address range of the VPC cannot be changed after the VPC is created. A VPC IPv4 address range may be as large as /16 (65,536 addresses) or as small as /28 (16 addresses), and it should not overlap any other net- work to which the VPC is to be connected.

## To simplify the initial user experience with Amazon VPC, AWS accounts have a default VPC created in each region with a default subnet created in each Availability Zone. The assigned CIDR block of the VPC will be 172.31.0.0/16. IPv6 is not enabled on the default VPC.

## AWS reserves the first four IPv4 addresses and the last IPv4 address of every subnet for internal networking purposes. For example, a subnet defined as a /28 has 16 available IPv4 addresses; subtract the 5 IPs needed by AWS to yield 11 IPv4 addresses for your use within the subnet.

## Here are the important points to understand about Elastic IP addresses for the exam:
### You must first allocate an Elastic IP address within a VPC and then assign it to an instance. Elastic IP addresses are specific to a region. An Elastic IP address in one region cannot be assigned to an instance within a VPC in a different region.
### There is a one-to-one relationship between private IPv4 addresses and Elastic IP addresses. Your instance will receive traffic destined to the private address mapping for your Elastic IP address.
### You can map Elastic IP addresses from one private IPv4 address to another, either in the same VPC or a different VPC, within the same region and account.
### Elastic IP addresses remain associated with your AWS account until you explicitly release them.You are not charged for the first Elastic IP address assigned to an instance, provided that the instance is running. Additional Elastic IP addresses per instance and Elastic IP addresses not associated with a running instance incur a small hourly charge.

## Here are the important points to understand about security groups for the exam: You can create up to 500 security groups for each VPC.
You can add up to 50 inbound and 50 outbound rules to each security group. You can associate up to five security groups with each network interface.
  
You can specify allow rules but not deny rules. This is an important difference between security groups and network ACLs.
You can specify separate rules for inbound and outbound traffic.

By default, no inbound traffic is allowed until you add inbound rules to the security group.

By default, new security groups have an outbound rule that allows all outbound traffic. You can remove the rule and add outbound rules that allow specific outbound traffic only.

Security groups are stateful. This means that responses to allowed inbound traffic are allowed to flow outbound regardless of outbound rules and vice versa. This is an important difference between security groups and network ACLs.
