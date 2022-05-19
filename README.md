# Check-in-app

Create and run docker container on Amazon ECS using CloudFormation and CLI.

-Use AWS CLI to create Amazon ECR repository

-Build docker image and push to ECR

-CloudFormation stack to create VPC, Subnets, InternetGateway etc

-CloudFormation stack to create IAM role

-CloudFormation stack to deploy docker container



The application was deployed using Amazon Elastic Container Service. This service allows using serverless deployment(Fargate)
It’s highly scalable and offers high availability and security. It’s deeply integrated with a variety of AWS services including ELB, VPC, IAM and many more. 
