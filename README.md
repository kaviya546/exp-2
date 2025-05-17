# exp-2

## Aim:  
To Create S3 bucket and EC2 Instances for Linux and Windows.  
## S3 Bucket:  
An Amazon S3 bucket is a public cloud storage resource available in Amazon Web Services 
(AWS) Simple Storage Service (S3) platform. It provides object-based storage, where data is 
stored inside S3 buckets in distinct units called objects instead of files.  
## EC2 Instance:  
An Amazon EC2 instance is a virtual server in Amazon's Elastic Compute Cloud (EC2) scalable 
compute platform for running applications on the Amazon Web Services (AWS) cloud. Amazon 
EC2 provides various types of instances of different sizes, with each comprising different 
configurations of central processing unit (CPU), memory, storage and networking resources to 
suit user needs and workloads.  
## Procedure:  
Step 1:  
● Log in to AWS Console  
Step 2:   
● Create an S3 Bucket  
● Navigate to the S3 service.  
● Click on Create bucket.  
● Enter a Bucket name and select a Region.  
● Configure Bucket settings as required (e.g., versioning, public access).  
● Click on Create bucket to finalize.  
Step 3:   
● Create an EC2 Instance (Linux)  
● Go to the EC2 service.  
● Click on Launch Instance.  
● Select an Amazon Machine Image (AMI) for Linux (Amazon Linux 2).  
● Choose an Instance Type (e.g., t2.micro for free tier).  
● Configure Instance Details, Storage, and Security Group.  
● Review and click Launch with a key pair (or create one if needed).  
Step 4:   
● Create an EC2 Instance (Windows)  
● Return to the EC2 service and click Launch Instance.  
● Select a Windows AMI (e.g., Windows Server 2019).  
● Choose the Instance Type.  
● Configure Instance Details, Storage, and Security Group.  
● Review and launch with a key pair (for future login).  
Step 5:  
● Verify and Connect to Instances.  
● Verify the status of both instances in the EC2 dashboard.  
● Connect to the Linux instance using SSH.  
● Connect to the Windows instance using RDP.  
## Output:  
![image](https://github.com/user-attachments/assets/e708d0d0-0664-4993-84f2-ddac5ad2529c)

## Result:  
Successfully created an S3 bucket and EC2 instances for both Linux and Windows, 
demonstrating cloud resource management on AWS
