FAQ - S3

 

Q. What is S3?

Q. What are the various types of Buckets?

Q. How Amazon ensure HA for S3?

Q. What is S3 Versioning and explain different States?

Q. What does a lifecycle rule consists of ?

Q. How to set an S3 Lifecycle configuration using AWS CLI ?

Q. How would you prevent versioning-related performance degradation issues?

Q. What are the different Storage classes in S3 ?

Q. How Amazon S3 manage costs, meet regulatory requirements, reduce latency?

Q. Why Amazon S3 is the best backend to store your state file ?

Q. Sample S3 bucket that follows industry best practices for security, data protection, and management.

Q. what are the Key S3 Metrics Available in CloudWatch?

Q. How does S3 handle access logging?

Q. What are presigned URLs?

Q. What is S3 Select and how is it used?

Q. What is Cross-Region Replication (CRR) in S3?

Q. Explain S3 Access Grants.

Q. S3 storage lens

 

=====

 

AWS - IAM FAQ

 

Q. What is AWS Identity and Access Management (IAM)?

Q. How does IAM work and what can I do with it?

Q. What are least-privilege permissions?

Q. What are IAM policies?

Q. Why should I use IAM roles?

Q. How to create policies usinh Create IAM policies (AWS CLI)?

Q. what types of policies?

Q. What are the Best Practices?

Q. Which policy attached to role to perform ECS task?

Q. How to assign User/Admin IAM policy for ECS management?

Q. If you're creating and managing AWS EKS service which IAM policies that allow you.

Q. What is the use of iam:PassRole permission?

Q. What is Trust policy?

Q. Can you restruct IAM user access by IP address?

Q. How to audit IAM changes?

Q. How Would you restrict an IAM role to access S3 only if MFA is enabled and the request comes from a specific VPC?

Q. What IAM roles typically used for each of these AWS services like S3, ECS, EKS, Lambda, ALB and EC2 with example?

 

 

=====

ECS - FAQ

 

Q. What is Amazon ECS?

Q. What are the different launch types in Amazon ECS?

Q. How does Amazon ECS ensure high availability (HA)?

Q. What is a Task Definition in Amazon ECS?

Q. What is a Service in Amazon ECS?

Q. How can I update a running service in Amazon ECS?

Q. What are the key metrics available in CloudWatch for Amazon ECS?

Q. How does Amazon ECS handle logging?

Q. What are IAM roles for tasks in Amazon ECS?

Q. What is ECS Service Auto Scaling?

Q. What is the difference between Amazon ECS and Amazon EKS?

Q. How does Amazon ECS integrate with AWS Fargate?

Q. What are ECS Clusters?

Q. What is a Container Instance in Amazon ECS?

Q. How can I monitor my Amazon ECS resources?

Q. What is the Amazon ECS Container Agent?

Q. How does Amazon ECS handle networking?

Q. What is the Amazon ECS Service Scheduler?

Q. How can I secure my Amazon ECS environment?

Q. What are the best practices for ECS security?

Q. How to create ECS using AWS CLI

 

 

=====

EKS - FAQ

Q. What is Amazon EKS?

Q. What is Kubernetes?

Q. Why should I use Amazon EKS?

Q. How does Amazon EKS work?

Q. Which operating systems does Amazon EKS support?

Q. What is the Amazon EKS Connector?

Q. Can I connect a cluster outside of an AWS Region?

Q. How does Amazon EKS handle security?

Q. What are the pricing models for Amazon EKS?

Q. How do I Get started with Amazon EKS using AWS cli?

Q. How do i upgragde my Kubernetes version in Amazon EKS?

Q. How does Amazon EKS handle high availability(HA)?

Q. How do I connect an on-premises Kubernetes cluster to Amazon EKS?

Q. How does Amazon EKS integrate with other AWS services?

Q. What are best practices on EKS?

Q. What are Kubernetes health checks and why are they important?

Q. What are the different types of health checks in Kubernetes?

Q. How do you configure a liveness probe in a Kubernetes pod?

Q. What is the purpose of a readiness probe?

Q. Can you explain the difference between liveness and readiness probes?

Q. What are best practices for configuring probes?

Q. What are common issues with health checks?

Q. What is the Horizontal Pod Autoscaler (HPA) in Kubernetes?

Q. How does the HPA work?

Q. How do you configure an HPA in Kubernetes?

Q. What metrics can be used with HPA?

Q. What are the benefits of using HPA?

Q. What are some common challenges when using HPA?

Q. How can you monitor the performance of HPA?

Q. Explain custom metrics for HPA.

 

=====

ALB - FAQ

 

Q. What is an Application Load Balancer (ALB)?

Q. How does ALB handle SSL termination?

Q. How does ALB perform health checks?

Q. What is path-based routing in ALB?

Q. How can I secure traffic between my ALB and my targets?

Q. How do I configure logging for my ALB?

Q. Can I configure multiple listeners on an ALB?

Q. How can I monitor my Application Load Balancer?

Q. How To enable monitoring for your Application Load Balancer (ALB) using the AWS Management Console and AWS CLI?

Q. What are the key metrics for ALB monitoring?

Q. What are best practices for ALB?

 

 

=====

 

AWS Lambda - FAQ

 

Q. What is AWS Lambda?

Q. What events can trigger an AWS Lambda function?

Q. How does AWS Lambda handle scaling?

Q. Can Lambda functions run on a timed schedule?

Q. What is the maximum execution duration for a Lambda function?

Q. How can a Lambda function retain state between invocations?

Q. What are some common use cases for AWS Lambda?

Q. What are the best practices for AWS Lambda?

Q. How do you create an AWS Lambda function using the AWS CLI?

Q. How can you update the code of an existing Lambda function using the AWS CLI?

Q. How do you add permissions to an AWS Lambda function to allow it to be triggered by an S3 event?

Q. How can you monitor AWS Lambda function performance, what important metrics to capture?

Q. How can you use AWS Lambda to process data from an Amazon S3 bucket?

Q. How can you use AWS Lambda to respond to HTTP requests?

Q. How can you use AWS Lambda to interact with Amazon DynamoDB?

Q. What are best practices for Lambda security?

Q. How to access lambda function with API gateway?

Q. What is a cold start in AWS Lambda?

Q. Why do cold starts happen in AWS Lambda?

Q. How can I reduce the impact of cold starts in AWS Lambda?

 

=====

 

Docker

 

 

Q. Write Dockerfiles in single github repo with different folders for python, nodejs and java applications with its dependencies.

Q. Write usage of Dockerfile key commands(instructions) like ENTRYPOINT, FROM, CMD, EXPOSE, ENV, COPY, ADD, ARGS and RUN etc.

Q. Write Docker compose file for multiple service application e.g front-end, backend and up/down all services.

Q. Automate the creation of an EC2 instance with a key pair, connect to the instance, log in, install Minikube, and deploy an application with deployment and ingress, all using Terraform.

Q. what are the best practices for docker?

 

 

=====

 

OIDC - FAQ

 

Q. What is an OIDC identity provider in AWS IAM?

Q. How do you create an OIDC identity provider in AWS IAM?

Q. What are the prerequisites for creating an OIDC identity provider in AWS IAM?

Q.How do you manage an OIDC identity provider using AWS CLI?

Q. What is the role of IAM policies in OIDC federation?

Q. Can you provide a Terraform resource block example for creating an OIDC identity provider?

Q. What are the security considerations when using OIDC identity providers in AWS?

Q. How do you troubleshoot common issues with OIDC federation in AWS?

Q. How do you update an existing OIDC identity provider in AWS IAM?

 

=====

 

AWS cloudwatch - FAQ

 

Q. What is Amazon CloudWatch?

Q. What can I use to access CloudWatch?

Q. What is Amazon CloudWatch Logs?

Q. What access management policies can I implement for CloudWatch?

Q. How does Amazon CloudWatch collect data?

Q. What are CloudWatch Alarms?

Q. Can I use CloudWatch to monitor my on-premises resources?

Q. What is CloudWatch Events?

Q. How long does CloudWatch retain data?

Q. What are best practices for using AWS CloudWatch effectively?

Q. What are key metrics and make list for monitoring ECS, EKS, Lambda, and ALB in AWS CloudWatch like container metrics etc.

 

------

X-rays

 

Q. What is AWS X-Ray?

Q. Why should I use AWS X-Ray?

Q. What is a trace in AWS X-Ray?

Q. How does AWS X-Ray help with debugging?

Q. How does AWS X-Ray work with AWS Lambda?

Q. What is a segment in AWS X-Ray?

Q. Can AWS X-Ray trace requests across AWS accounts?

Q. How can I visualize traces in AWS X-Ray?

Q. What are sampling rules in AWS X-Ray?

Q. How to set up AWS X-Ray for my application?

Q. What are common issues during setup?

Q. What are best practices for using X-Ray?

 

=====

 

AWS CloudTrail

 

Q. What is AWS CloudTrail?

Q. What are the benefits of using AWS CloudTrail?

Q. How can I view my account activity with AWS CloudTrail?

Q. What is a CloudTrail trail?

Q. Can I use AWS CloudTrail to monitor multiple AWS accounts?

Q.  What is AWS CloudTrail Lake?

Q. How long does AWS CloudTrail retain data?

Q. What are CloudTrail Insights?

Q. How to set up a CloudTrail trail using AWS CLI?

Q. what are best practices for CloudTrail?

Q. What are CloudTrail log file formats?

 
