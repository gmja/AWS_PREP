## MariaDB has a page size of 16 KB. To write 200 MB (204,800 KB) of data every second, it would need 12,800 IOPS. Oracle, PostgreSQL, or Microsoft SQL Server, which all use an 8 KB page size, would need 25,600 IOPS to achieve the same throughput
## MariaDB - 16KB page size - IOPS and other DBs - 8 KB

## General-purpose SSD storage allocates 3 IOPS per GB, up to 10,000 IOPS. Therefore, to get 600 IOPS, you'd need to allocate 200 GB.
## ( 3 IOPS/GB for GP2)

## When you provision IOPS using IO1 storage, you must do so in a ratio no greater than 50 IOPS for 1 GB. Allocating 240 GB of storage would give you 12,000 IOPS ( 50 IOPS/GB for IO1)

## RCU - 1 SC /4KB  - 2 RCU EC - 4KB

## WCU - 1 per 1 KB

## Elastic Beanstalk takes care of the ongoing underlying deployment details for you, allowing you to focus exclusively on your code.

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

