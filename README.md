
## Ex.4 Deployment and configuration of a Private Cloud  in AWS

## Aim:
To set up of a Private Cloud  in AWS.

## Setting up of a private cloud in AWS:

Setting up a private cloud within AWS, also known as a Virtual Private Cloud (VPC),
involves creating a logically isolated virtual network that you can use to launch AWS
resources. This provides you with full control over your virtual networking environment,
including resource placement, connectivity, and security.
Amazon Virtual Private Cloud (Amazon VPC) gives you full control over your virtual
networking environment, including resource placement, connectivity, and security. Get
started by setting up your VPC in the AWS service console. Next, add resources to it such as
Amazon Elastic Compute Cloud (EC2) and Amazon Relational Database Service (RDS)
instances. Finally, define how your VPCs communicate with each other across accounts,
Availability Zones, or AWS Regions.

## Procedure:
## 1. Plan Your VPC:
## ● Determine your needs:
Define your use case, including application requirements, security needs, and
compliance standards.
## ● Plan IP address ranges:
Choose appropriate IP address ranges for your VPC and subnets to avoid conflicts.
## ● Select Availability Zones:
Decide which Availability Zones (AZs) you'll use for your resources, considering
redundancy and performance.
## ● Plan internet connectivity:
Determine if you need public internet access and how to configure it.
## ● Define security:
Plan your security groups, network ACLs, and access controls to ensure a secure
environment.

## 3. Create Your VPC:
Sign in to AWS Management Console: Access the VPC console and navigate to the VPC dashboard.
 Choose "Create VPC": Initiate the VPC creation process.
Configure VPC details: Enter the VPC name, CIDR block, Availability Zones, and
other necessary settings.
Create subnets: Define subnets within your VPC to isolate different parts of your
network.
Create route tables: Specify how traffic is routed within and outside the VPC.
 Create security groups: Define access control rules for your resources.

## 4. Deploying Resources:
Launch EC2 instances: Create and launch virtual machines within your VPC.
 Set up RDS instances: Deploy databases for your applications.
Configure networking: Connect your resources to the appropriate subnets, security
groups, and route tables.
Deploy other AWS services: Integrate other services like S3 for storage and Lambda for serverless computing.

## 5.Managing and Monitoring:
Use AWS CloudWatch: Monitor your VPC and resources for performance and
health.
Configure logging and auditing: Track access and activity within your VPC for
security and compliance.
Implement security best practices: Regularly review and update your security
configuration.
Scale and adjust as needed: Adjust your VPC infrastructure to meet changing
demands.

##  Output:

## Create VPC:

![Screenshot 2025-05-13 132155](https://github.com/user-attachments/assets/a97fd5ad-b36b-46c0-a049-25e9e9b9ade5)

## Configure subnets:

![Screenshot 2025-05-13 132309](https://github.com/user-attachments/assets/e418b198-4f05-4d26-8072-529dce5d904a)

![Screenshot 2025-05-13 132325](https://github.com/user-attachments/assets/77255511-c7b8-490e-a288-148e39f13e13)

## Setting Internet Gateway:

![Screenshot 2025-05-13 132456](https://github.com/user-attachments/assets/a68bd286-8101-4b4c-aef7-5d2be2c40ec2)

![Screenshot 2025-05-13 132511](https://github.com/user-attachments/assets/74252b1a-add0-47c1-b482-185e0ee263ba)

![Screenshot 2025-05-13 132525](https://github.com/user-attachments/assets/2be72b29-321a-498d-9994-856aa199e7c2)

## Creating Route Table:

![Screenshot 2025-05-13 132731](https://github.com/user-attachments/assets/ed8136ca-ff43-4627-9582-bb9a2c470a54)

## Configuring Route Table:

![Screenshot 2025-05-13 132743](https://github.com/user-attachments/assets/ee51f140-2bb4-4cfe-8d01-2ed65c6a4f2c)

## Editing Routes:

![Screenshot 2025-05-13 132801](https://github.com/user-attachments/assets/99d77a5f-95b7-4f70-889a-2795c53c8b0a)

## Creating Route Table:

![Screenshot 2025-05-13 132833](https://github.com/user-attachments/assets/bc81ab2e-3f62-4d72-b038-cbd939745206)

## Result:

Thus, a private cloud on AWS involves using VPCs has been created for  a dedicated, isolated network where we can manage our resources and control access according to our requirements.

