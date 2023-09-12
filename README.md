# EC2
Amazon is a web service that enables you to launch and manage server instances in Amazon’s data centers using APIs or available tools and utilities. We can use Amazon EC2 server instances at any time, for as long as you need.



## FEATURES
On Demand – It can be accessed from anywhere
Elasticity – It would be elastic when accessing Amazon Instances
Resource pulling – Amazon does multi-tenancy.  In simpler terms, they would have a huge data center which they would be virtualizing and offering through various channels.

## FEATURES iN EC2
It is flexible as it comes with multiple flavours and serves a lot of OS. It comes with different Linux layers from Ubuntu and Fedora to name a few
It is much secure with elements like security groups and private key files
It’s a controlled environment(once the user gets virtual machine, then it will completely be in the user control)
It comes with pre-built AMIs which is the major USP of Amazon along with a strong ecosystem

## HOW EC2 WORKS
Here AMI is a pre-configured bundle software. In short, an ISO format of Amazon.  We select an AMI and launch an instance from the AMI. Once instance is available, we can install any software as part of instance and make our own AMI.

*Note*  that Amazon charges the user right from the pending state of instance to instance termination. There is also a special type of Amazon instance available called EDS. They provide you with an additional stage called stop instance which will decrease cost.

EC2 Instance Types & Size
General Purpose (M1 &M3)- It is the  1st generation. The M1 & M3 have similar kind of instances. The only difference is that M3 will be new and it will provide better I/O. It will also cost less. For application hosting and web server usage, it would be recommended to go for M1 & M3.

Compute Optimized Instances (C1 & CC2)- They provide instances of high compute power. They have a higher ratio of vCPUs to memory than other families and lowest cost per vCPU. If you have higher CPU requirement, go for C1 & CC2. Here caching activity need more memory utilization.

Storage Optimized Instances (HI1 & HS1)- In some case, we need more storage optimized instances, (HI1 & HS1) as it will provide higher throughput, yet be a right fit for NoSQL Database

 Memory Optimized Instances (M2 & CR1)- Instances of this family are optimized for memory-intensive applications. They have the lowest cost per GiB of RAM.
 Services
 
#### *What is AWS Auto Scaling?*
AWS Auto Scaling is a service that helps the user to monitor applications and automatically adjusts the capacity to maintain steady, predictable performance at the lowest possible cost.

##### *Benefits of Auto Scaling*

Better fault tolerance
High availability of resources
Better cost management
High reliability of resources
The high flexibility of resources
