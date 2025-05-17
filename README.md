Overview
DevOps Challenge! In this use case, you will demonstrate your skills in containerization, Infrastructure as Code (IaC), CI/CD, and cloud deployment using AWS services. You will be working with a simple python flask application.
Challenge Structure
Use below deployment tracks. 
1.	Amazon EKS Deployment 
Common Requirements
Regardless of the track you choose, you will be working with the following common elements:
1.	Microservices: You will be provided with flask microservices - The code for these services can be found in the Sample Microservices Code file.
2.	Containerization: You need to containerize these microservices using Docker.
3.	Infrastructure as Code (Terraform):
o	Set up a Terraform project structure supporting multiple environments (dev, staging, prod).
o	Provision the following AWS resources:
	VPC with public and private subnets across two availability zones
	IAM roles and security groups
	S3 bucket for Terraform state storage
	DynamoDB table for state locking
	(Other resources specific to your chosen track)
4.	Terraform State Management:
o	Implement remote state storage using S3
o	Set up state locking with DynamoDB
o	Configure workspace separation for different environments
5.	GitHub Actions for IaC:
o	Create workflows for:
	Terraform fmt and validate on all PRs
	Terraform plan on pull requests
	Terraform apply on merges to main branch
6.	CI/CD: Implement a CI/CD pipeline using GitHub Actions for your application code.
7.	Monitoring and Logging: Set up basic monitoring and logging using AWS CloudWatch.

Evaluation Criteria
While specific criteria vary by track, you will generally be evaluated on:
1.	Correct implementation of the chosen deployment platform
2.	Quality and security of the IaC implementation
3.	Effectiveness of the CI/CD pipeline
4.	Containerization best practices
5.	Monitoring and logging setup
6.	Documentation quality
7.	Overall architecture and security considerations
8.	Proper implementation of Terraform state management and collaboration features
Getting Started
1.	Review the common requirements and evaluation criteria.
2.	Choose your deployment track: EKS
3.	Use the provided microservices code as a starting point for your application.




Amazon EKS Deployment 
Objective
Deploy the containerized microservices to Amazon Elastic Kubernetes Service (EKS), demonstrating your skills in Kubernetes, containerization, and AWS services.
Technical Requirements
1.	Infrastructure as Code (Terraform)
o	Provision a VPC with public and private subnets
o	Set up an EKS cluster
o	Configure necessary IAM roles and security groups
o	Set up an ECR repository for your container images
2.	Containerization
o	Create a Dockerfile for the microservices
o	Build and push the Docker image to ECR
3.	Kubernetes
o	Create Kubernetes deployment manifests
o	Set up a service and ingress for your applications
4.	CI/CD (GitHub Actions)
o	Implement a workflow for Terraform (lint, plan, apply)
o	Create a workflow for building and pushing Docker images
o	Implement a workflow for deploying to EKS

5.	Monitoring and Logging
o	Set up CloudWatch for cluster and application logging
o	Implement Prometheus and Grafana for monitoring
Deliverables
1.	GitHub repository containing:
o	Terraform code
o	Dockerfiles
o	Kubernetes manifests
o	GitHub Actions workflows
o	Application code (provided github url)
2.	Documentation:
o	Architecture diagram
o	Setup and deployment instructions
o	Monitoring and logging overview
Evaluation Criteria
1.	EKS cluster configuration and security
2.	Kubernetes resource management and best practices
3.	CI/CD pipeline efficiency and reliability
4.	IaC quality and modularity
5.	Containerization best practices
6.	Monitoring and logging effectiveness
7.	Documentation clarity and completeness

Sample python application code
    geeekfa/Api-Flask



