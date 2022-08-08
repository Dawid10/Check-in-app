# Check-in-app

Create and run docker container on Amazon ECS using CloudFormation and CLI.

-Use AWS CLI to create Amazon ECR repository

-Build docker image and push to ECR

-CloudFormation stack to create VPC, Subnets, InternetGateway etc

-CloudFormation stack to create IAM role

-CloudFormation stack to deploy docker container



The application was deployed using Amazon Elastic Container Service. This service allows to use serverless deployment(Fargate).
It’s highly scalable and offers high availability and security. It’s deeply integrated with a variety of AWS services including ELB, VPC, IAM and many more. 


For this project I have started by building infrastructure (Vpc, 2 public and 2 private subnet, route tables, public ip, natgateway and security groups). I also created Aplocation load balancer to enable me to create ECS cluster using Fargate.
Subsequently, I created Task definitions with the image for frontend. I developed a template for IAM roles and policies so the task can download image from ecs and upload logs to cloudwatch.

