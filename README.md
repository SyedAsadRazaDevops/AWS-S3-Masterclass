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
- first this first, crate an user for s3 in **IAM** service.
- click on **user**.
- enter **Username =xxx** select Type **programmatic access**
- Set permissions (use existing policy) and **created it**.
- go to terminal of linux server run the command `aws configure`
- enter the access & securit key of new user.
- **NOTE:** it best to define the region as default or given on every command on terminal by `--region ue-west-1`.
- confirm by run this command `aws s3 ls`.

## -2 What is S3 ?
- store object **(file/videos/picture)**.
- dont need to create **OS**.
- object can uptu **5TB**
- highly durable 99.999999999 **(11 9's)**.
- data is replicated to multiple regions
- highly scalable
- highly avalible
- be secure by **IAM roles**
- upload and downlod data using web

**S3 HAS A UNIVERSAL NAMESPACE**

## -3 S3 is used for?
- bacckup and archive
- static website hosting
- bigdata and aynalytics
- content storage and distribution
- DR plans

**YOU CAN CREATE UP TO 100 BUCKETS BY DEFAULT (add more by request)**
> S3 value formate be: [ Bucket + Key + VersionID ] 
> Object key used UFT-8 encoding 
> s3 doest provid object locking
> s3 is secure by default
> s3 is RESTful web service
**S3 CHARGE FOR** (storeage,request,data transfer,mangment funtions,S3 inventory)

