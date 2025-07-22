## AWS (Amazon Web Services)

# What is AWS?
Amazon Web Services (AWS) is a cloud platform offered by Amazon that lets people and companies use IT services like storage, servers, and databases through the internet. 
Instead of buying and maintaining physical computers, you can "rent" these services online and only pay for what you use.
AWS provides tools to do it easily and quickly. It offers over 200 services such as 
EC2 for virtual servers
S3 for storing files 
RDS for managing databases
and Lambda to run code without servers.

## Why use AWS?
The below are the most important reasons for using AWS:

1. On-Demand Resources
With AWS, you don’t need to set up your computers or servers. You can quickly use services like storage, databases, and virtual machines over the internet. 
It is like turning on a switch, use what you need, when you need it.

2. Pay-as-You-Go Pricing
AWS doesn't ask you to buy anything upfront. You are charged only for the time and the amount of services you use. 
If you use a server for 2 hours, you only pay for 2 hours. This helps save money and avoid waste.

3. Global Infrastructure
AWS has data centres across the globe. So, whether your users are in India, the US, or Europe your app can reach them quickly.
Also, if your business grows and you need more power or storage, AWS can easily scale up without downtime.

4. Reliability and Performance
AWS is built to be strong and dependable. It uses multiple backup systems, so even if one fails, others keep your data and apps running.
You get fast performance and high availability so your services rarely go down.

5. Everything from one Platform
In AWS, everything you need is available on one platform. You can launch virtual servers using Amazon EC2 to run your applications, store files and media using Amazon S3, and manage databases easily with Amazon RDS.
In addition to this, AWS allows you to analyze large amounts of data, build and run artificial intelligence models, and even host complete websites.
All these services are accessible from a single dashboard, making it simple to build, deploy, and manage projects without setting up any physical hardware.

## AWS Fundamentals
Regions: AWS provide the services with respective division of regions. Regions are based on geographical locations, each with one or more data centers. Based on need and traffic of users, the scale of data centers is depended to facilitate users with low-latencies of services.

Availability Zones (AZ): To protect data centers from natural calamities or any other disasters. Data centers are divided into isolated locations called Availability Zones to enhance fault tolerance and disaster recovery management.

Global Network Infrastructure: AWS ensures the reliability and scalability of services through setting up its own AWS Network Infrastructure globally. It helps in better management of data transmissions for optimized performance and security reliance.

# AWS Services

## Compute Services
EC2 (Elastic Compute Cloud): Launch and manage scalable virtual servers in the cloud.

Lambda: Run code without managing servers, triggered by events.

ECS (Elastic Container Service): Run Docker containers at scale.

EKS (Elastic Kubernetes Service): Managed Kubernetes service for container orchestration.

Elastic Beanstalk: Deploy and scale web apps automatically.

Lightsail: Easy-to-use cloud platform for simpler applications.

Outposts: Bring AWS services to your on-premises data center.

## Storage Services
S3 (Simple Storage Service): Store and retrieve unlimited objects in the cloud.

EBS (Elastic Block Store): Block-level storage volumes for EC2 instances.

EFS (Elastic File System): Scalable file storage for Linux workloads.

Glacier: Low-cost storage for long-term archiving and backups.

Storage Gateway: Connect on-premises systems to AWS storage.

## Database Services
RDS (Relational Database Service): Managed relational databases (MySQL, PostgreSQL, etc.).

DynamoDB: Fully managed, serverless NoSQL key-value database.

Aurora: High-performance relational DB compatible with MySQL/PostgreSQL.

## Networking & CDN
VPC (Virtual Private Cloud): Isolated network environment for your AWS resources.

Route 53: Scalable and highly available DNS and domain name service.

CloudFront: Content delivery network (CDN) for low-latency delivery.

API Gateway: Create, publish, and manage secure APIs.

Direct Connect: Dedicated network connection from your premises to AWS.

## Security, Identity & Compliance
IAM (Identity and Access Management): Control access to AWS services and resources.

Cognito: User authentication and access control for web/mobile apps.

KMS (Key Management Service): Create and control encryption keys.

Shield: Protect applications from DDoS attacks.

WAF (Web Application Firewall): Filter malicious web traffic to applications.

## DevOps & Monitoring
CloudWatch: Monitor AWS resources and applications in real-time.

CloudTrail: Track and log all API calls across your AWS environment.

CodeCommit: Secure Git-based source code repository.

CodeBuild: Build and test code in the cloud.

CodeDeploy: Automate software deployments to compute services.

CodePipeline: Automate the software release process (CI/CD).

ECR (Elastic Container Registry): Store, manage, and deploy Docker container images.

OpsWorks: Configuration management using Chef or Puppet.

## Management & Governance
CloudFormation: Provision infrastructure as code using templates.

AWS Config: Record and evaluate configuration changes of AWS resources.

AWS Organizations: Manage and control multiple AWS accounts centrally.

Systems Manager: Manage and automate EC2 and on-premises server configurations.

Trusted Advisor: Provides real-time recommendations to improve security, performance, and cost-efficiency.
