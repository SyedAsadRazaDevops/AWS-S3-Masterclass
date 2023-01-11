Deep dive into S3 and learn all you need to know in this comprehensive Masterclass

### Amazon Simple Storage Service (S3) is the most feature-rich storage platform available in the cloud today.
S3 provides developers with secure, durable, and highly-scalable cloud storage. Its easy-to-use web interface allows you to quickly store and retrieve any amount of data from anywhere on the web.

### The majority of users aren't getting everything they can from S3.
With the variety of use cases and features, it is time consuming to read through all of the documentation that is out there on S3.

## topics:
- Basics of S3
- Access Control
- Logging and Monitoring
- Data Protection
- Lifecycle Management
- Automated Event Notifications
- Performance Optimization
- Serverless Static Website Hosting
- Practical Uses of S3 Using Cloudberry Backup


## -1 Create user and configre CLI
  1- first this first, crate an user for s3 in **IAM** service.
  2- click on **user**.
  3-enter **Username =xxx** select Type **programmatic access**
  4- Set permissions (use existing policy) and **created it**.
  5- go to terminal of linux server run the command `aws configure`
  6- enter the access & securit key of new user.
  7- **NOTE:** it best to define the region as default or given on every command on terminal by `--region ue-west-1`.
  8- confirm by run this command `aws s3 ls`.
