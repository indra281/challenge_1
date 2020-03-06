# challenge_1
Solution for tech challenge 1


The services/processes(Mixing, Sheet, forming, baking etc) will be deployed as a micro services in a dockerized containers in AWS fully Managed Container Service(Fargate). 

The containers will be highly scalable and resilient to Data centre failure.They will be backed by Auto Scaling which scales them on the basis of the utilization of the resources.The load will be distributed using Elastic Load Balancer. 

The Database will be deployed in another AWS fully Managed Relational database service(RDS) which makes it easy to set up, operate, and scale a relational database in the cloud. Here I have assumed that the database will be Relational database,if in case the dataase is NoSQL, we can use DynamoDB service of AWS.

For fast retrieval of data, we will use Elastic cache service of AWS, Amazon It works as an in-memory data store and cache to support the most demanding applications requiring sub-millisecond response times.it offers fully managed Redis and Memcached . 

To autmate the software delivery process, such as initiating automatic builds and then deploying to fargate ,we will use CodePipeline(Code Commit, Code Build and Code Deploy), a service that builds, tests, and deploys code every time there is a code change, based on the release process models.

AWS S3 can be used to store object file like images and videos. It provides object storage through a web service interface. Amazon S3 uses the same scalable storage infrastructure that Amazon.com uses to run its global e-commerce network. 

NAT gateway can provide private instances with access to the Internet for essential software updates while blocking incoming traffic.


