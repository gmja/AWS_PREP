### Cross-zone load balancing reduces the need to maintain equivalent numbers of instances in each enabled Availability Zone, and improves your application's ability to handle the loss of one or more instances. However, we still recommend that you maintain approximately equivalent numbers of instances in each enabled Availability Zone for higher fault tolerance.

## 
![](https://user-images.githubusercontent.com/26511983/74153243-ca28a500-4bd5-11ea-9d28-ff6f638e2035.png)

### Storage optimized instances are designed for workloads that require high, sequential read and write access (IOPS)

### Memory optimized instances are designed to deliver fast performance for workloads that process large data sets in memory

### Compute optimized instances are for compute-bound applications high-performance processors, batch processing workloads and media transcoding

### General purpose instances provide a balance of compute, memory, and networking resources

## Lambda 

### To prevent your Lambda function from running indefinitely, you specify a timeout. When the specified timeout is reached, AWS Lambda terminates execution of your Lambda function. default timeout is 3 seconds and the maximum execution duration per request in AWS Lambda is 900 seconds, which is equivalent to 15 minutes.

### the AWS Lambda limits the total concurrent executions across all functions within a given region to 1000, If that limit is exceeded, the function will be throttled but not terminated..

### recursive code in your Lambda function does not directly result to an abrupt termination of the function execution. This is a scenario wherein the function automatically calls itself until some arbitrary criteria is met. This could lead to an unintended volume of function invocations and escalated costs, but not an abrupt termination because Lambda will throttle all invocations to the function.


## 

### To enable the cross-region replication feature in S3, the following items should be met:

### The source and destination buckets must have versioning enabled.
### The source and destination buckets must be in different AWS Regions.
### Amazon S3 must have permissions to replicate objects from that source bucket to the destination bucket on your behalf.


##

![](https://user-images.githubusercontent.com/26511983/74157741-69ea3100-4bde-11ea-99c7-2befecec82ca.png)

##

#### An Elastic IP address doesn’t incur charges as long as the following conditions are true:

-The Elastic IP address is associated with an Amazon EC2 instance.
-The instance associated with the Elastic IP address is running.
-The instance has only one Elastic IP address attached to it.

## (IAM) database authentication

### You can authenticate to your DB instance using AWS Identity and Access Management (IAM) database authentication. IAM database authentication works with MySQL and PostgreSQL. With this authentication method, you don't need to use a password when you connect to a DB instance. Instead, you use an authentication token.

### You can also still use standard database authentication.

### using the --ssl-ca parameter can provide SSL connection to your database

## SCP OU

![](https://user-images.githubusercontent.com/26511983/74158167-35c34000-4bdf-11ea-999f-789c9f9ce1d6.png)


## CloudFront

### The "Cache-Control" and "Expires" headers control how long objects stay in the cache. The "Cache-Control max-age" directive lets you specify how long (in seconds) you want an object to remain in the cache before CloudFront gets the object again from the origin server.

## 

![](https://user-images.githubusercontent.com/26511983/74158480-c4d05800-4bdf-11ea-999e-1f7b62a4eb5d.png)

## Elastic Beanstalk vs ECS
### Elastic Beanstalk supports the deployment of web applications from Docker containers. 
### "automatically" handle all the tasks such as balancing load, auto-scaling, monitoring, and placing your containers across your cluster. You will have to manually configure these things if you wish to use ECS.

![](https://user-images.githubusercontent.com/26511983/74158767-445e2700-4be0-11ea-8419-438ed75e590a.png)

![](https://user-images.githubusercontent.com/26511983/74158829-60fa5f00-4be0-11ea-8347-40ccb981e555.png)

## S3 multi-upload 
### when your object size reaches 100 MB, you should consider using multipart uploads instead of uploading the object in a single operation
![](https://user-images.githubusercontent.com/26511983/74158897-7bccd380-4be0-11ea-953e-5726e6583e03.png)
##

### SSH -22 RDP - 3389 port

## Multi-AZ DB

### When you provision a Multi-AZ DB Instance, Amazon RDS automatically creates a primary DB Instance and synchronously replicates the data to a standby instance in a different Availability Zone (AZ). 

### Increased database availability in the case of system upgrades like OS patching or DB Instance scaling.

### It makes the database fault-tolerant to an Availability Zone failure

## Spot Instance

### If your Spot instance is terminated or stopped by Amazon EC2 in the first instance hour, you will not be charged for that usage. However, if you terminate the instance yourself, you will be charged to the nearest second.

### If the Spot instance is terminated or stopped by Amazon EC2 in any subsequent hour, you will be charged for your usage to the nearest second. If you are running on Windows and you terminate the instance yourself, you will be charged for an entire hour.


## CloudFront Versioning vs Invalidation

### If you want to update your files frequently, AWS recommends that you primarily use file versioning for the following reasons:

### -Versioning enables you to control which file a request returns even when the user has a version cached either locally or behind a corporate caching proxy. If you invalidate the file, the user might continue to see the old version until it expires from those caches.
### -CloudFront access logs include the names of your files, so versioning makes it easier to analyze the results of file changes.
### -Versioning provides a way to serve different versions of files to different users.
### -Versioning simplifies rolling forward and back between file revisions.
### -Versioning is less expensive.

## CodeCommit vs Code Deploy

![](https://user-images.githubusercontent.com/26511983/74159837-0c57e380-4be2-11ea-8724-38ad886090fb.png)


## 


## 
![](https://user-images.githubusercontent.com/26511983/71539011-fbd1ff00-28fa-11ea-9aec-bc59ae4cedf3.png)

# EC2

![](https://user-images.githubusercontent.com/26511983/71486505-4c9f0600-27dc-11ea-8f35-e27aaa61a080.png)

![](https://user-images.githubusercontent.com/26511983/71486537-735d3c80-27dc-11ea-985a-52d70417df2d.png)

![](https://user-images.githubusercontent.com/26511983/71487894-5415dd80-27e3-11ea-87f9-6714583a793c.png)

![](https://user-images.githubusercontent.com/26511983/71488178-c63af200-27e4-11ea-83fd-310ee0a50c5a.png)

![](https://user-images.githubusercontent.com/26511983/71492611-2ee29880-27fe-11ea-9d6d-c575952902ad.png)

![](https://user-images.githubusercontent.com/26511983/71492792-859ca200-27ff-11ea-8e20-5fc8ac6a8081.png)

![](https://user-images.githubusercontent.com/26511983/71493633-dadbb200-2805-11ea-9938-94aa8dbe49c0.png)

![](https://user-images.githubusercontent.com/26511983/71493645-fa72da80-2805-11ea-9369-cefb3cc0ce83.png)

![](https://user-images.githubusercontent.com/26511983/71496116-17fc7000-2817-11ea-8e5c-24efeee96845.png)

![](https://user-images.githubusercontent.com/26511983/71496166-53973a00-2817-11ea-940c-e63dfdf9be00.png)

![](https://user-images.githubusercontent.com/26511983/71496363-94dc1980-2818-11ea-9945-5641293bfd54.png)

![](https://user-images.githubusercontent.com/26511983/71496510-48450e00-2819-11ea-9dce-a06e96d226c8.png)

![](https://user-images.githubusercontent.com/26511983/71496722-5a737c00-281a-11ea-8664-d189dcf3afd9.png)

# Dedicated Instance vs Dedicated Host

## Start/Stop Dedicated Instance , Host may change(H-107) whereas Dedicated Host Host will remian same(H-101) 
## Hardware bound licences - Dedicated Host
## Cost is high for Dedicated Host
### An application you want to run on EC2 requires you to license it based on the number of physical CPU sockets and cores on the hardware you plan to run the application on. Which of the following tenancy models should you specify?

![](https://user-images.githubusercontent.com/26511983/71526820-29d52600-289e-11ea-9ec5-d824b3de9639.png)

# CloudWatch

![](https://user-images.githubusercontent.com/26511983/71527281-55591000-28a0-11ea-8b1f-aa49c11ccfa0.png)

![](https://user-images.githubusercontent.com/26511983/71527335-90f3da00-28a0-11ea-95e8-4697f443388a.png)

![](https://user-images.githubusercontent.com/26511983/71527905-006ac900-28a3-11ea-8af3-38abb2901fcc.png)

![](https://user-images.githubusercontent.com/26511983/71528347-095c9a00-28a5-11ea-9d6e-f35a3946a102.png)

![](https://user-images.githubusercontent.com/26511983/71528694-ab30b680-28a6-11ea-9cb9-89e9f22039a2.png)

![](https://user-images.githubusercontent.com/26511983/71528862-8a1c9580-28a7-11ea-81a7-b2bdda4a56e0.png)

![](https://user-images.githubusercontent.com/26511983/71528910-d49e1200-28a7-11ea-925d-80958054476b.png)

![](https://user-images.githubusercontent.com/26511983/71528949-01522980-28a8-11ea-927f-b1658338ae32.png)

![](https://user-images.githubusercontent.com/26511983/71528981-1e86f800-28a8-11ea-907c-ad4aae94d501.png)

![](https://user-images.githubusercontent.com/26511983/71529222-53477f00-28a9-11ea-81f4-741e06ea58b1.png)

![](https://user-images.githubusercontent.com/26511983/71529400-18921680-28aa-11ea-8fe9-fd5bcbbef71c.png)

![](https://user-images.githubusercontent.com/26511983/71560695-d811d480-2a32-11ea-97ac-a206df62f411.png)

![](https://user-images.githubusercontent.com/26511983/71560622-499d5300-2a32-11ea-9264-ac73d472c4dc.png)

![](https://user-images.githubusercontent.com/26511983/71560650-9123df00-2a32-11ea-978e-aa221d027b7d.png)

![](https://user-images.githubusercontent.com/26511983/71560750-84ec5180-2a33-11ea-995c-7c5854bba7ba.png)


# Copy Volumes to instance in a different AZ

## Attach a Volume to EC2-1 in AZ-1
## Mount the volume and write a new file
### lsblk - to see partitions 
### mount /dev/sda2 /mnt/mydisk
### umount /dev/sda2  
## Take a snapshot of Volume
## Create new volume from snapshot in AZ-2
## Attach the volume to EC2-2 in AZ-2
## Mount and see content of new file 

![](https://user-images.githubusercontent.com/26511983/71563402-529f1c00-2a54-11ea-9e2a-00948ed5a0e7.png)

![](https://user-images.githubusercontent.com/26511983/71563426-e83aab80-2a54-11ea-8f9b-ff1ae8d60cea.png)

## Snapshot is just a Backup of Volume or Instance
![](https://user-images.githubusercontent.com/26511983/71563442-289a2980-2a55-11ea-8983-db0988d6b9b1.png)


## HA across Regions using Route 53

![](https://user-images.githubusercontent.com/26511983/71563743-24243f80-2a5a-11ea-998e-6f2027a3433a.png)

![](https://user-images.githubusercontent.com/26511983/71563764-651c5400-2a5a-11ea-87af-41babaff2110.png)

![](https://user-images.githubusercontent.com/26511983/71563775-9c8b0080-2a5a-11ea-80ef-7d9a1b07db64.png)

## ELB

![](https://user-images.githubusercontent.com/26511983/71563781-e2e05f80-2a5a-11ea-98b1-909e24ee2749.png)


![](https://user-images.githubusercontent.com/26511983/71629359-ba737500-2bc2-11ea-94b7-d1a21075beb5.png)

![](https://user-images.githubusercontent.com/26511983/71629917-aed57d80-2bc5-11ea-98ea-07ec1f581f4b.png)

### The NAT gateway goes in the public subnet
### When you delete your NAT gateway, remember to also delete the elastic IP it used.
![](https://user-images.githubusercontent.com/26511983/71630055-9e71d280-2bc6-11ea-8a80-a4be9490365b.png)

### Add route to the The NAT gateway in the private subnet route table
![](https://user-images.githubusercontent.com/26511983/71630148-1f30ce80-2bc7-11ea-8cca-a2ef131a87e1.png)


### Black Hole - deleting NAT Gateway would cause this
![](https://user-images.githubusercontent.com/26511983/71630247-923a4500-2bc7-11ea-8dc5-f8db35485879.png)


## NAT Instance select AMI of type -nat-

![](https://user-images.githubusercontent.com/26511983/71630309-ddecee80-2bc7-11ea-8b69-790e81ec63d2.png)

## For NAT to work, disable Source/Destination check
### NAT does not accept Traffic and it just forwards traffic from one instacne to other
### Destination Traffic is not really for NAT insatnce
![](https://user-images.githubusercontent.com/26511983/71630949-7b95ed00-2bcb-11ea-9d14-7018d6f70656.png)

![](https://user-images.githubusercontent.com/26511983/71631026-ff4fd980-2bcb-11ea-94a8-2f6a5a4d55b6.png)

## Add NAT Insatcne to the Private subnet Route Table
![](https://user-images.githubusercontent.com/26511983/71631085-535abe00-2bcc-11ea-8eaf-1448aa7dddf5.png)


## VPC Peering

![](https://user-images.githubusercontent.com/26511983/71633551-67a5b780-2bda-11ea-8c18-09bd2cb074b1.png)

![](https://user-images.githubusercontent.com/26511983/71635502-d12dc200-2bea-11ea-8338-0634b4b0731c.png)

## Accept peering request
![](https://user-images.githubusercontent.com/26511983/71635532-2538a680-2beb-11ea-84ad-f29b0772c690.png)

## Edit Route Table for both routes tables of the Subnets to add VPC peering connection
![](https://user-images.githubusercontent.com/26511983/71635602-9bd5a400-2beb-11ea-8980-5b0315be07ad.png)

![](https://user-images.githubusercontent.com/26511983/71635627-c58ecb00-2beb-11ea-8849-5ba9fda76b7d.png)

## Other subnet
![](https://user-images.githubusercontent.com/26511983/71635653-f0791f00-2beb-11ea-9c93-ae1f71d9a131.png)

## VPC Peering is possible across regions and Accounts
![](https://user-images.githubusercontent.com/26511983/71635721-9cbb0580-2bec-11ea-8e63-4479d3b208f7.png)

![](https://user-images.githubusercontent.com/26511983/71635743-f1f71700-2bec-11ea-98fe-78729fb4b0a3.png)

![](https://user-images.githubusercontent.com/26511983/71635774-0cc98b80-2bed-11ea-9fa0-24522802d8e1.png)

![](https://user-images.githubusercontent.com/26511983/71635786-2d91e100-2bed-11ea-9340-a552d3fa0e5e.png)

## VPC peering will only allow to communicate between instances 
## You can not route your traffic further thru Gateways/NAT instances/VPC endpoints

![](https://user-images.githubusercontent.com/26511983/71635825-9da06700-2bed-11ea-8085-3d698db2db60.png)

![](https://user-images.githubusercontent.com/26511983/71635850-e9531080-2bed-11ea-96c4-86c7606fa87c.png)

![](https://user-images.githubusercontent.com/26511983/71635864-0d165680-2bee-11ea-9dc0-d999c0c1e41d.png)

## VPC Endpoint

![](https://user-images.githubusercontent.com/26511983/71637540-0518df80-2c0b-11ea-87ca-17e74b5edf18.png)

## ELB 

![](https://user-images.githubusercontent.com/26511983/71637787-a0618300-2c12-11ea-9dab-f6540b1eb9ab.png)

![](https://user-images.githubusercontent.com/26511983/71637901-1d422c00-2c16-11ea-9afa-31455804a2dc.png)

![](https://user-images.githubusercontent.com/26511983/71637915-81fd8680-2c16-11ea-8453-7ca46ac68257.png)

## ELB With Auto scaling group

![](https://user-images.githubusercontent.com/26511983/71637917-98a3dd80-2c16-11ea-8bfd-2527b624c6e3.png)

![](https://user-images.githubusercontent.com/26511983/71637928-c4bf5e80-2c16-11ea-8b6a-fb80e4eb042c.png)

