8.16 AWSome Day in 新竹
===
# Infrastructure
- 22 regions
- 2 AZ per region
## CloudFront
- Similiar to CDN
- Reduce latency when user access the data
# Basic service
## EC2
- Resizable compute capacity
- AMI (Amazon Machine Image) config for open an instance
  - Based on
    - Region
    - OS
    - Artitecture(32, 64bits)
    - Launch permission
    - Storage for booting device
  - Recommend to update often
- Status
  - Pending
    - Check for network and hardware
  - Termination protection
  - rebooting is differed from stop and restart
    - the charge will not be recount
- Marketplace
  - Can buy some pre-configured infrastructure, like EC2 instance.
- Most of them are Intel CPU
- NEW MACHINE IS CHEAPER THAN OLD MACHINE
- Instance Metadata
  - Data about my instance
- Instance User Data
  - Can be passed when launching
  - Like install and start HTTP Server
- Payment
  - Pay by demand (per second for Linux, per minute for Windows)
  - One or three year terms can take cheaper price
  - Scheduled instance
  - Like running at the end of every month
  - Spot
    - Bid on unused instance (can take discount)
  - Dedicated instance & host
## ECS & ECR
- Cluster
  - Include docker instance
- Agent
  - Run on Docker instance
- Task Defination
- AWS fargate
  - No need to manage cluster
## AWS Lambda
## AWS VPC
- Decide network env (like public or private)
- Subnet
  - Public, private, VPN only
- Security in VPC
  - Security Group
    - Check when in
  - Network ACL
    - Check when both in and out
- VPN
## S3
### Lifecycle management
## EBS
- Persitent block level storage (for EC2)
# Security
## AWS Multi-Tier Security Group
# Database
## RDS
- Auto backup
- Manual Snapshot
- Multi AZ
## DynamoDB
- Partition Key
- Sort Key
## Aurora
- Aurora serverless
- Develope by AWS
- Compatible with MySQL and PostgreSQL
# Machine learning


