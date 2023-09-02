# AWS
Deployment Model of cloud 
1.Public cloud 
2.Provate cloud 
3.Hybrid cloud 
What is Ec2 ?
- Elastic compute cloud (Ec2) provides scalable computing capacity in the aws cloud .
- AMzon Ec2 having two storage option i.e EBS and instance and instance store .

Type of instances 
1.General Purose Instances 
- General purpose instances provide a balance of compute, memory and networking resources, and can be used for a variety of diverse workloads.
- 3 series in General Purpose
  A ,M and T series.
  
2. Compute Optimized
Compute Optimized instances are ideal for compute bound applications that benefit from high performance processors. Instances belonging to this category are well suited for batch processing workloads, media transcoding, high performance web servers, high performance computing (HPC), scientific modeling, dedicated gaming servers and ad server engines, machine learning inference and other compute intensive applications.
   
3. Memory Optimized
-Memory optimized instances are designed to deliver fast performance for workloads that process large data sets in memory.
- Mostly we are using in databases 
-R ,x and Z series
4.Storage Optimized
  - Storage optimized instances are designed for workloads that require high, sequential read and write access to very large data sets on local storage. They are optimized to deliver tens of thousands of low-latency, random I/O operations per second (IOPS) to applications.
    - Perfect examal is Youtube where many users are reaching to the application and so required high read write  
  - I ,D and H series 
5. Accelerated Computing
  Accelerated computing instances use hardware accelerators, or co-processors, to perform functions, such as floating point number calculations, graphics processing, or data pattern matching, more efficiently than is possible in software running on CPUs.
 - P,G and F series instances
- Live streming of game ,Insta Live ,Fb live
6. High Memory Instance

__________________________________________________________________________________________
Instance purchasing options
1. On-Demand Instances
- Pay, by the second, for the instances that you launch.
- In case of Linux if you use the instance for 45min you need to pay for 45min but in windows we have to pay on hourly basis .
- They are sutable for testing and development

2. Dedicated Instances
-  Dedicated Instances are EC2 instances that run on hardware that's dedicated to a single customer.
-   Dedicated Instances that belong to different AWS accounts are physically isolated at a hardware level, even if those accounts are linked to a single payer account.
-    Dedicated Instances might share hardware with other instances from the same AWS account that are not Dedicated Instances.

3.Dedicated Host
  - An Amazon EC2 Dedicated Host is a physical server with EC2 instance capacity fully dedicated to your use.
4. Spot Instances
  - Spot Instances are a cost-effective choice
  - AWS gave free instances on very low cost .
  - Generly we can use this for testing beacuse aws can terminate with 2min of notice

5.Schedule Instance 
- AWS Scheduled Instances comes in handy when there are applications that need to be run on a daily, weekly, or monthly basis with a regular start time and duration throughout the year.
- suppose you need the instance for 8hours per day 9am to 5pm Monday to friday so aws gave the facility to book the instance for whole year .
- If your not using in between 9am to 5pm its not going to reduce the cost.

6 . Reserved Instance
- We can reserv the instance for year or 3 years for the same cost it is 75% cheper than on demand .
-------------------------------------------------------------------------
Que:1 Suppose you terminate the instance than what will happen with EBS volumes   ?
Que:2 Suppose you terminate the instance than what will happen with temp voulume which is attched with the server .
Que: EBS vs S3 vs Instance Store.




 
