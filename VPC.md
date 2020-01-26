![](https://user-images.githubusercontent.com/26511983/73139219-5c0aac80-4031-11ea-8feb-8342105d4ff9.png)

![](https://user-images.githubusercontent.com/26511983/73139296-46e24d80-4032-11ea-84fd-625fa91a0c2d.png)

![](https://user-images.githubusercontent.com/26511983/73139307-66797600-4032-11ea-86a4-e2475e2ca28d.png)

![](https://user-images.githubusercontent.com/26511983/73139340-c1ab6880-4032-11ea-9e8e-6b164d11a94d.png)

![](https://user-images.githubusercontent.com/26511983/73139529-814cea00-4034-11ea-9528-01251411b80b.png)

![](https://user-images.githubusercontent.com/26511983/73139600-2f589400-4035-11ea-8a35-5f4744262582.png)

![](https://user-images.githubusercontent.com/26511983/73139606-46978180-4035-11ea-8609-1295333ff9f0.png)

![](https://user-images.githubusercontent.com/26511983/73139638-a3933780-4035-11ea-8757-faf5d96ba4fc.png)

![](https://user-images.githubusercontent.com/26511983/73139687-2b794180-4036-11ea-9998-04a08a085e90.png)

![](https://user-images.githubusercontent.com/26511983/73139723-8f036f00-4036-11ea-96ea-d49abe4f0770.png)

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
####  You must first allocate an Elastic IP address within a VPC and then assign it to an instance. Elastic IP addresses are specific to a region. An Elastic IP address in one region cannot be assigned to an instance within a VPC in a different region.
####  There is a one-to-one relationship between private IPv4 addresses and Elastic IP addresses. Your instance will receive traffic destined to the private address mapping for your Elastic IP address.
####  You can map Elastic IP addresses from one private IPv4 address to another, either in the same VPC or a different VPC, within the same region and account.
####  Elastic IP addresses remain associated with your AWS account until you explicitly release them.You are not charged for the first Elastic IP address assigned to an instance, provided that the instance is running. Additional Elastic IP addresses per instance and Elastic IP addresses not associated with a running instance incur a small hourly charge.

## Here are the important points to understand about security groups for the exam: You can create up to 500 security groups for each VPC.
#### You can add up to 50 inbound and 50 outbound rules to each security group. You can associate up to five security groups with each network interface.
  
#### You can specify allow rules but not deny rules. This is an important difference between security groups and network ACLs.You can specify separate rules for inbound and outbound traffic.

#### By default, no inbound traffic is allowed until you add inbound rules to the security group.

#### By default, new security groups have an outbound rule that allows all outbound traffic. You can remove the rule and add outbound rules that allow specific outbound traffic only.

#### Security groups are stateful. This means that responses to allowed inbound traffic are allowed to flow outbound regardless of outbound rules and vice versa. This is an important difference between security groups and network ACLs.

#### Instances associated with the same security group cannot communicate with each other unless you add rules to the security group allowing the security group to communicate within itself.

#### You can change which security groups an instance is associated with after launch, and the changes will take effect in seconds.
# 

![](https://user-images.githubusercontent.com/26511983/71450760-d217ad00-272d-11ea-8199-9e0edfd8d22b.png)

![](https://user-images.githubusercontent.com/26511983/71450783-7ef22a00-272e-11ea-8296-77cf7aca894a.png)

## VPC Peering
![](https://user-images.githubusercontent.com/26511983/71450803-dd1f0d00-272e-11ea-88eb-ca723114ac88.png)


## Placement Groups

![](https://user-images.githubusercontent.com/26511983/71450811-00e25300-272f-11ea-969f-4d0db74cc47a.png)

## Elastic Network Interfaces
![](https://user-images.githubusercontent.com/26511983/71450821-28d1b680-272f-11ea-9358-d4604bc6554b.png)

# VPC Flow Logs provide a periodic view of network flow information. Log data is pushed to Amazon CloudWatch Logs approximately every 10 minutes. VPC Flow Logs are useful for understanding network traffic, including anomaly detection and troubleshooting.


