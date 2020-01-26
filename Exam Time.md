## An internet gateway serves two purposes: 
### 1. provide a target in your VPC route tables for internet-routable traffic, 
### 2. perform network address translation (NAT) for instances that have been assigned public IPv4 addresses.

## Amazon Glacier standard retrievals typically retrieval within 3 – 5 hours  
## Amazon Glacier bulk retrievals: retrievals typically complete within 5 – 12 hours  

https://aws.amazon.com/premiumsupport/knowledge-center/bucket-policy-encryption-s3/



## When you create a new AWS account, this role is automatically created and configured for you. Service-Linked Roles for AWS Support
### AWSServiceRoleForSupport 
### AWSServiceRoleForTrustedAdvisor

## Use access keys to make programmatic calls to AWS from the AWS CLI, Tools for PowerShell, the AWS SDKs, or direct AWS API calls. You can have a maximum of two access keys (active or inactive) at a time. Max 2

## CloudFront key pairs - You use key pairs in Amazon CloudFront to create signed URLs. 

## X.509 certificate - You use X.509 certificates to make secure SOAP-protocol requests to some AWS services Max 2

## MariaDB has a page size of 16 KB. To write 200 MB (204,800 KB) of data every second, it would need 12,800 IOPS. Oracle, PostgreSQL, or Microsoft SQL Server, which all use an 8 KB page size, would need 25,600 IOPS to achieve the same throughput
## MariaDB - 16KB page size - IOPS and other DBs - 8 KB

## General-purpose SSD storage allocates 3 IOPS per GB, up to 10,000 IOPS. Therefore, to get 600 IOPS, you'd need to allocate 200 GB.
## ( 3 IOPS/GB for GP2)

## When you provision IOPS using IO1 storage, you must do so in a ratio no greater than 50 IOPS for 1 GB. Allocating 240 GB of storage would give you 12,000 IOPS ( 50 IOPS/GB for IO1)

## RCU - 1 SC /4KB  - 2 RCU EC - 4KB

## WCU - 1 per 1 KB

## Elastic Beanstalk takes care of the ongoing underlying deployment details for you, allowing you to focus exclusively on your code.

## ONly one pulbic IP 
![](https://user-images.githubusercontent.com/26511983/73138739-d0dae800-402b-11ea-8dbf-51e271f021cd.png)


## EC2 Instance type can be changed after stopping instance
![](https://user-images.githubusercontent.com/26511983/71789572-741e7b80-2ff1-11ea-8bbb-433fd58b418b.png)

![](https://user-images.githubusercontent.com/26511983/71770010-6da6db80-2eed-11ea-93b6-3426316b0e9c.png)

![](https://user-images.githubusercontent.com/26511983/71772511-c5573e00-2f11-11ea-8522-cac79951048e.png)

![](https://user-images.githubusercontent.com/26511983/71772613-39deac80-2f13-11ea-99bd-403a60158d12.png)

![](https://user-images.githubusercontent.com/26511983/71772635-98a42600-2f13-11ea-8e0d-3e5405390962.png)


## You can share a private image / snapshots  with another account or make it public
![](https://user-images.githubusercontent.com/26511983/71772783-cf2f7000-2f16-11ea-98d5-f8a33f56f0f9.png)

![](https://user-images.githubusercontent.com/26511983/71772818-afe51280-2f17-11ea-9fc9-958ec110fcf2.png)


## NAT Gateway needs EIP
![](https://user-images.githubusercontent.com/26511983/71772849-3bf73a00-2f18-11ea-88c3-38b974e0df35.png)

## You can change security groups on a running instance
## Instance can have multiple security groups

![](https://user-images.githubusercontent.com/26511983/71772889-09017600-2f19-11ea-96ec-be95f23bc903.png)

![](https://user-images.githubusercontent.com/26511983/71772902-38b07e00-2f19-11ea-8530-70d7886c46b0.png)


## Create ELB and attach two instances
![](https://user-images.githubusercontent.com/26511983/71773030-8332fa00-2f1b-11ea-82dd-9e066f6472cf.png)

## Route 53 with ELB

![](https://user-images.githubusercontent.com/26511983/71773020-626aa480-2f1b-11ea-80c1-0112169ff97c.png)

## Extend Root volume Without Stopping the Windows Instance

![](https://user-images.githubusercontent.com/26511983/71773943-cac18200-2f2b-11ea-9398-e5f7693d3afa.png)


## EC2

![](https://user-images.githubusercontent.com/26511983/71784439-2e45c100-2fb9-11ea-8f53-5228c7dde8ce.png)

![](https://user-images.githubusercontent.com/26511983/71784432-2423c280-2fb9-11ea-85b3-333ab5002d2c.png)


## Role

![](https://user-images.githubusercontent.com/26511983/71784500-c5127d80-2fb9-11ea-8f7f-910dac99cd74.png)


![](https://user-images.githubusercontent.com/26511983/71784544-38b48a80-2fba-11ea-8955-01480358f8e9.png)


![](https://user-images.githubusercontent.com/26511983/71784994-fbeb9200-2fbf-11ea-8a71-3f4cf80b8dfe.png)

![](https://user-images.githubusercontent.com/26511983/71785588-fc3b5b80-2fc6-11ea-8cc2-070bc448d0a0.png)

## User Partition for Cassandra/Hadoop and Kafka
![](https://user-images.githubusercontent.com/26511983/71785608-27be4600-2fc7-11ea-819e-36a1ed3a07d9.png)

## Cluster
![](https://user-images.githubusercontent.com/26511983/71785650-a5825180-2fc7-11ea-88a4-037a5142a5ea.png)

## Spread Restricted to 7 EC2 per AZ
![](https://user-images.githubusercontent.com/26511983/71785651-b0d57d00-2fc7-11ea-8c5c-111e59f45fa1.png)

## Partition Restricted to 7 Parttitions and each Parttition can host 100s of EC2

![](https://user-images.githubusercontent.com/26511983/71785663-e67a6600-2fc7-11ea-9b5a-090fc4e46255.png)

![](https://user-images.githubusercontent.com/26511983/71785687-20e40300-2fc8-11ea-96c2-36339ae11555.png)

![](https://user-images.githubusercontent.com/26511983/71785709-5f79bd80-2fc8-11ea-8432-39f5d42c97d6.png)

![](https://user-images.githubusercontent.com/26511983/71785730-b7b0bf80-2fc8-11ea-880c-158eb968c7d9.png)

![](https://user-images.githubusercontent.com/26511983/71785739-d4e58e00-2fc8-11ea-8dc6-e1c29c60a2b5.png)

![](https://user-images.githubusercontent.com/26511983/71785795-7d93ed80-2fc9-11ea-84ad-db70805b7600.png)

![](https://user-images.githubusercontent.com/26511983/71785805-b338d680-2fc9-11ea-8862-3ae64e3f5090.png)

### The requested number of I/O operations per second that the volume can support. For Provisioned IOPS (SSD) volumes, you can provision up to 50 IOPS per GiB. For General Purpose (SSD) volumes, baseline performance is 3 IOPS per GiB, with a minimum of 100 IOPS and a maximum of 10000 IOPS. General Purpose (SSD) volumes under 1000 GiB can burst up to 3000 IOPS.

## GP2
![](https://user-images.githubusercontent.com/26511983/71785865-55f15500-2fca-11ea-923a-122e5cb07e23.png)

## IO1
![](https://user-images.githubusercontent.com/26511983/71785871-673a6180-2fca-11ea-90f4-2dbd62b8602b.png)

## HDD IOPS n/A
![](https://user-images.githubusercontent.com/26511983/71785894-95b83c80-2fca-11ea-831a-e414de9ff489.png)

![](https://user-images.githubusercontent.com/26511983/72213476-43d55200-34b5-11ea-9f97-edabfef4cb31.png)

## Incremental snapshots.. You do not have to worry about deleting snapshots

![](https://user-images.githubusercontent.com/26511983/72213494-a0387180-34b5-11ea-9f3f-7a74f13ba7bf.png)

![](https://user-images.githubusercontent.com/26511983/72213502-b5150500-34b5-11ea-9b3a-f806eb880e2b.png)

https://www.youtube.com/watch?v=l9yg2mPvEFg

![](https://user-images.githubusercontent.com/26511983/72213516-10df8e00-34b6-11ea-9da4-413a765333b7.png)

![](https://user-images.githubusercontent.com/26511983/72213518-21900400-34b6-11ea-802f-957c77b268a6.png)

![](https://user-images.githubusercontent.com/26511983/72213533-792e6f80-34b6-11ea-9236-8a29cb7840e3.png)

![](https://user-images.githubusercontent.com/26511983/72231385-cbd45e00-3580-11ea-8f12-2d9208ec8c01.png)

![](https://user-images.githubusercontent.com/26511983/72231448-135aea00-3581-11ea-85a6-f7f7150dfe9d.png)

![](https://user-images.githubusercontent.com/26511983/72231465-443b1f00-3581-11ea-8088-3c1c92389a8b.png)

![](https://user-images.githubusercontent.com/26511983/72231733-b2ccac80-3582-11ea-86e6-8e1dbefca45b.png)

![](https://user-images.githubusercontent.com/26511983/72231878-63d34700-3583-11ea-8f08-d9d0b53b3c35.png)

![](https://user-images.githubusercontent.com/26511983/72231941-c88ea180-3583-11ea-9150-04b2859af902.png)

![](https://user-images.githubusercontent.com/26511983/72232118-b4976f80-3584-11ea-9bca-803ae93a5318.png)

![](https://user-images.githubusercontent.com/26511983/72232238-5dde6580-3585-11ea-8f61-1c07244e9d5b.png)

![](https://user-images.githubusercontent.com/26511983/72232325-160c0e00-3586-11ea-925e-1fe822556795.png)

![](https://user-images.githubusercontent.com/26511983/72232361-59ff1300-3586-11ea-94dc-0204c620cf66.png)

![](https://user-images.githubusercontent.com/26511983/72443392-cbe87f80-3773-11ea-9593-7ea3181c9870.png)

![](https://user-images.githubusercontent.com/26511983/72443573-1964ec80-3774-11ea-9ed8-3ea692a51750.png)

![](https://user-images.githubusercontent.com/26511983/72645082-5aa5f980-3938-11ea-99da-9ff13f23bbc3.png)

![](https://user-images.githubusercontent.com/26511983/72646996-10734700-393d-11ea-9974-fa7719d284cd.png)


http://knowledgehills.com/aws/my-day-at-aws-csaa-exam.htm

###  EBS
### If my App needs large sequential I/O what to use?
Answer: use Throughput Optimized HDD (st1).
Pillars: Cost effective Pillar and  High performant architecture pillar

### If my App needs write intensive, small, random I/O  how to design to improve i/o performance?
Answer:  RAID 0 stripe multiple EBS volumes together for high I/O performance was the best available choices since there was no choice given for Provisioned IOPS volumes.
Pillars: Cost effective Pillar and  High performant architecture pillar

### Your on premises server has application using proprietary file system. How do you migrate to AWS?
Answer: Use EBS volumes with EC2. Other choices included EFS, Stored Volumes etc. Keyword is proprietary file system since EFS supports NFS and stored volumes support iSCSI.
Pillar: Operational Excellence Pillar

### CloudWatch
EC2 calls API on behalf of users (did not mention what API or which users. Assume AWS API and IAM users). How to monitor when API calls 1) reach >5 per second 2) >3000/hour 3)Count of API calls by user
Two Multiple Answers: Enable CloudTrail and Use Custom CloudWatch metrics to monitor API calls. Wrong choices included CW Metrics (custom keyword missing), CW Logs etc.
Pillar: Operational Excellence


### CloudTrail
Question about Enabling CloudTrail automatically for future regions using turning on CloudTrail for All Regions

### CloudFront
EC2 web server is serving static and dynamic content. Due to this you are getting high CPU utilization. How to reduce the load?
Answer: Use cloudfront with EC2 origin. Wrong choices included not so obvious ones such as cloudfront with url signing, elasticache
Pillar: Performance
### How to serve private S3 content from CloudFront?
Answer: By using Origin Access Identifier for S3 and URL signing. The keyword here is “private” hence you need to disable public access to the S3 bucket and allow only OAI from CF to access. URL signing is must since you don’t want people to reuse the urls as they expire after sometime.
Pillar: Security, Performance

### RDS
On premise db needs to be migrated to AWS. Requirement is redundant data for DR in three Availability Zones. How to achieve?
Answer: AWS RDS Aurora. Since the keyword is 3 AZs. Choices included RDS MySQL with Multi AZ, DynamoDB, RedShift etc.
Pillar: Reliable Pillar

### Elasticache
Need to design web session storage for million user web site, what do you recommend?
Answer is elasticache. Other choices that are not good: Redshift, S3, EFS, RDS etc.
Pillars: Performance Efficiency pillar
Many questions came up, where elasticache was present as one of the choices but it was not the correct choice based on the keywords.
For example you need a data storage for key/value and JSON documents with unlimited capacity and highly scalable, where DynamoDb is the correct choice since unlimited capacity and scaling is needed.

### Cognito
Need to design and develop quickly a mobile application solution to let users login with MFA. What do you suggest?
Answer is Cognito as it supports ready to use identity management solution and provides MFA thru SMS. Wrong choices included RDS, S3 policies (to bait you for MFA), IAM etc.
Pillars: Security, Cost Optimization

### S3
How to access S3 privately from on premises VM’s connected via VPN to AWS. Choices included S3 VPC endpoint via AWS EC2 proxy, IP Whitelisting CGW, IP Whitelisting VPG.
Answer: Not sure. Recommend reading and understanding S3 private connections (by pass internet) from VPNs and VPCs
Pillar: Security
How to access S3 from VPC private subnet?
Answer: VPC endpoint. Other choices included NAT Gateway, Internet Gateway etc
Pillar: Security and Cost pillars
Only CEO needs to access daily reports on S3 which are very confidential. How to provide this?
Answer: S3 presigned URLs. Choices included AWS KMS key encryption, AWS S3 Key encryption, MFA, IAM Roles etc.
Security Pillar

### SQS
Mission critical Order processing system to be designed on EC2 using ELB/Auto Scaling. How do you decouple?
Answer: SQS. Wrong choices included SNS, SES etc. but did not include SWF hence SQS is better option among the available ones.
Pillars: Reliability pillar

### Lambda
After user uploads an image, EC2 copies it to S3 then another EC2 constantly checks S3 and retrieves image and processes and copies the resultant image to another bucket. What do you recommend to re-design decoupled?
Answer: Use Lambda since they mentioned re-design and de-couple. Other choices included SNS, SES etc. but no SQS. So Lambda was the best choice.
Pillars: Reliability pillar
EC2 has a script that runs hourly to download new files from S3 and process. How do you improve this for availability?
Answer: Invoke Lambda when a new file is created on S3
Pillar: Reliability and Performance pillars

### Kinesis
Car rental agency needs to monitor GPS locations from all cars to make sure they are not driven too far. If they get few thousand data points every hour how to process this data?
Answer: Use Kinesis Firehose and store in S3 and analyze. Keyword to understand is every hour, meaning its a data stream coming in 24/7. None of the other choices (EC2, SQS, Lambda) have streaming data features
Pillars: Reliability Pillar (Data loss is not acceptable)
Application Load Balancer:
I got 3 or 4 questions on this topic and relating to the choice of ALB over CLB. Luckily I was reading the same topic on AWS documentation in the morning and I was able to answer correctly.
A set of EC2 instances are running a set of web services using different ports. How do you balance the load?
Answer: ALB. Since multiple web services are running across multiple ports spanning multiple EC2s. CLB can’t distinguish by port and CLB can balance a single service.
Pillars: Reliability Pillar
A three tier web application is using ELB as front end, web tier running on EC2 instances and db tier running on RDS instances. How can you introduce fault tolerance?
Answer: Classic ELB in front of EC2s. The takeaway keyword here is instances (plural). There was one reasonably good looking choice “CLB in front of RDS instances” but then I remembered CLB can only balance web traffic and not RDS traffic.
Pillars: Reliability Pillar


### DynamoDB
You have 60 TiB indexed data which is growing exponentially, that you want to move to AWS. Which unlimited durable storage would you recommend?
Answer: DynamoDB since the keyword indexed suggests that this data is indexed and searchable/queryable. Other choices included RDS, S3 etc. Unlimited and durable apply to S3 as well but DynamoDB is better than S3 for indexed data.
Pillar: Reliability Pillar
In house MySQL is unable to perform even with the highest available CPU/Memory configuration. This system reads small 400 kb data items,  one record at a time. Customer willing to move to a new architecture. What do you suggest?
Answer: DynamoDB since keywords “one record” and “small items” is used meaning JOINS are not performed. The language keyword here is “willing to move” meaning they are ok to go from relational to NoSQL

### EC2
Which EC2 would you recommend for cost effective servers that you will use for the next three years continuously at the same capacity? A) Regional Standard Reserved Instances B) Regional Convertible Instances C) Standard Reserved Instances
Answer: Please read Jeff’s blog post and understand the minute details. I think I made a mistake here. Did not expect such complicated, in depth question in an associate level exam.
Pillar: Cost effective pillar
IAM role for EC2 question. Simple and straight forward.
What would you recommend to run batch processes every Mon/Thu/Fri from 10 to 12?
Answer: Scheduled EC2
Pillar: Cost effective pillar

### VPC
How to access S3 from VPC private subnet?
Answer: VPC endpoint. Other choices included NAT Gateway, Internet Gateway etc
Pillar: Security and Cost pillars
Three tier application with ELB, web servers and db servers need to have no internet connectivity from tier 2, 3
Answer: ELB in public subnet, Web servers in private subnet and db servers in private subnet
Pillar: Security pillar
Bastion Host 2 questions

### NAT 4 questions
You have a NAT and EC2 instances in private subnet. How to make is more Reliable?
Answer: Add NAT’s in all AZs
Pillar: Reliable Pillar
Migrating from NAT instance with custom scripts that perform auto scaling. What do you recommend?
Answer: NAT gateway in all AZs
Pillar: Reliable Pillar
Basic question about Private EC2 needing to access internet for patches. How to achieve this?
Answer: Use NAT Gateway. Choices included all gateways such as NAT GW,  IGW, VPG, Customer GW etc.
Pillar: Scalable Performant Architecture
EFS
Your auto scaling group runs 10 to 50 Linux instances that need to have access to common storage which is mountable. What do you recommend?
Answer: Common and mountable keywords imply EFS
Route53
One question relating to Failover policy

### ECS
Need to design system running on docker containers that need orchestration.
Answer: ECS

### Storage Gateway
Your legacy app using iSCSI needs to have storage solution on AWS for all new storage
Answer: Cached Volumes since new keyword is used meaning all the new data must be stored on AWS. Stored volumes is a wrong choice here since with SV, you store all new data locally with a backup on AWS for redundancy purpose only.
