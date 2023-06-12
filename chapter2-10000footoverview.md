# AWS Services
### AWS Global Infrastructure
#### Services
Compute, Storage, DBs, Migration, Networking & Content Delivery, Dev Tools, Mgmt Tools, Media Services, Machine Learning, Analytics, Security, Identity & Compliance, Mobile Servcs, AR/VR, App Integrations, Customer Engagement, Business Productivity, Dsktp & App Streaming, IOT, Game Dev
#### Regions
**Region:** Geographical Area, consist of 2 or more AZ
**Availability Zone:** Data Center
2017 - 16 Regions & 44 AZs
2018 - 24 Regions & 61 AZs
**Edge Location:** Caching Content for Regions (i.e. If someone wants a file from London and is based in Argentina, edge location cache that content close there so next time someone wants that content, can access faster to that)
***Edge Locations:*** 96 

### Services
#### Compute
**EC2** Elastic Compute Cloud (VMs in AWS platform)
**EC2 Container Service** Run/Manage Docker Container service at Scale
**Elastic Beanstalk** who developers that don't understand AWS, so you focus only on pushing your code and scales automatically
**Lamda** Code that you upload to cloud and you can execute (Like Cloud functions)
**Lightsail** VPS (Virtual Private Server) Service, Configure your own server, fix IP, SSH access and such
**Batch** batch computing in the cloud

#### Storage
**S3** (Simple Storage Service, SSS, s3) Object Based Storage, Buckets in the cloud
**EFS** (Elastic File System) storage files 
**Glacier** (Data Archiver) Archive Data that you don't need to look to frequently
**Snowball** Way to bring huge amount of data into AWS data center (physically, they sent you a device, you move it there and then you send it back to aws)
**Storage Gateway** VM appliances, VM that you stored on your datacenters

#### DataBases
**RDS** (Relational Db server) MySql, MSSQL, PostgresSQL, etc.
**DynamoDB** (Non-Relational DB) 
**Elasticcache** Caching query for DB servers and such, store procedures, products, caching service
**RedShift** Datawearehouse, Really complex Queries, BI Services

#### Migration
**AWS Migration Hub** Tracking Service, Track migration on your services as you migrate
**Application Discovery Service** Automated set of tools, tracking dependencies for your application
**Db Migration Service** Migrate on Premise to AWS
**Snowball** Migrate Large Data (Repeated on Storage)

#### Networking & Content Delivery
**VPC** (Virtual Private Cloud) Virtual Data Center, you configure Firewalls, etc. (Complicated)
**CloudFront** (CDN) Media Assets, Files, such, store close to other zones, so it can be accessed by edge locations
**Route53** DNS service
**API Gateway** Creating own APIs to other services to talk to
**Direct Connect** A Way of running dedicated line of corporate head office * IMPORTANT IN THE EXAM

#### Developer Tools
**CodeStar** Group of developer, Project Manager your code, CICD and such
**CodeCommit** Git, Repository
**CodeBuild** Compile your code and produce packages ready to deploy
**CodeDeploy** Deployment to instances, lamda functions and such
**CodePipeline** CICD Server
**XRay** Debug your serverless applications
**Cloud9** IDE web  

#### Management Tools
