# Terraform Exercise

## Introduction

Having a robust and reliable cloud infrastructure is crucial for businesses to deliver seamless services to their customers. High availability and fault tolerance are two essential components of such an infrastructure. 

In order to achieve this, many organizations turn to infrastructure automation tools like Terraform to deploy and manage their cloud resources.

We’ll explore how to use Terraform to deploy a high availability and fault-tolerant cloud environment on AWS, complete with an Auto Scaling Group (ASG) spanning two Availability Zones in private subnets of a custom VPC. 

We’ll also look at how to front the ASG with an Application Load Balancer (ALB) placed in public subnets, with appropriate gateway and route table configurations.
