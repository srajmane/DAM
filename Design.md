## System Design

- **Users**: 
Interact with Digital Asset Management system using different user. To manage all types of user (team member, third-party user) I am using AWS IAM. Using IAM
we can create differnt group, role based access to users. This will provide security for our cloud native application.

- **Amazon Route 53**: 
Amazon Route 53 connects user requests to infrastructure running in AWS like Amazon EC2 instances, Elastic Load Balancing load balancers, 
or Amazon S3 buckets – and can also be used to route users to infrastructure outside of AWS.

- **Elastic Load Balancing**
Elastic Load Balancing (ELB) automatically distributes incoming application traffic across multiple targets and virtual appliances in one or more Availability Zones.

- **AWS S3**
Amazon Simple Storage Service (Amazon S3) is a highly scalable, cloud storage service that stores object data within buckets. As we are storing images, video. s3 bucket will
manage our blob storage.

- **Amazon CloudFront**
Amazon CloudFront is a large scale, global, and feature rich CDN that provides secure, scalable and intelligently integrated application delivery. Amazon CloudFront is a fast
content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally with low latency, high transfer speeds, all within a developer-friendly environment.

- **CDN**
A content delivery network (CDN) is a network of interconnected servers that speeds up webpage loading for data-heavy applications. CDN can stand for content delivery network or content distribution network. 

- **DB server**
We can use DynamoDB DB server here to store all the database. Amazon DynamoDB is a fully managed, serverless, key-value NoSQL database designed to run high-performance applications at any scale.

- **Cloud Search/ Elastic Search**
Amazon CloudSearch is a managed service in the AWS Cloud that makes it simple and cost-effective to set up, manage, and scale a search solution.

- **CloudWatch**
Amazon CloudWatch collects and visualizes real-time logs, metrics, and event data in automated dashboards to streamline your infrastructure and application.

- **Crawler**
A crawler accesses your data store, extracts metadata, and creates table definitions in the AWS Glue Data Catalog.

- **Web App Deployment – AWS Elastic Beanstalk**
AWS Elastic Beanstalk helps you deploy and manage web applications with capacity provisioning, app health monitoring, and more.


