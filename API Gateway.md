![](https://user-images.githubusercontent.com/26511983/70857282-fdd69f80-1eb0-11ea-9200-5d5ca36747ff.png)

## API Gateway supports multiple mechanisms of access control using AWS Identity and Access Management (IAM), AWS Lambda authorizers, and Amazon Cognito.

### Resource policies let you create resource-based policies to allow or deny access to your APIs and methods from specified source IP addresses or VPC endpoints. 
#### if you are an AWS Partner who offers APIs over a SaaS model, you can take advantage of the new Amazon API Gateway resource policies feature to control access to your APIs using predefined IP address ranges. 

##### only from specified source IP address ranges or CIDR blocks, without writing any code

![](https://user-images.githubusercontent.com/26511983/74088644-25d02280-4a5e-11ea-8ebd-6344a05cb6cc.png)

### IAM roles and policies can be used for controlling who can create and manage your APIs as well as who can invoke them.  

### Endpoint Policies for Interface VPC Endpoints allow you to attach IAM resource policies to interface VPC endpoints to improve the security of your private APIs.  

### Lambda authorizers are Lambda functions that control access to REST API methods using bearer token authentication as well as information described by headers, paths, query strings, stage variables, or context variables request parameters.  

### Amazon Cognito user pools let you create customizable authentication and authorization solutions for your REST APIs. Amazon Cognito user pools are used to control who can invoke REST API methods.  
