**Title:** Understand the working of AWS - Create AWS-EC2-InstanceCreation, AWS-S3-ObjStorage

**Objective:**
The objective of this lab is to provide a comprehensive understanding of how to work with key AWS services, specifically focusing on the creation of EC2 instances and managing object storage using AWS S3. By the end of this experiment, participants will have a clear understanding of the step-by-step processes involved in setting up a virtual server (EC2 instance) and storing data securely and efficiently using S3, empowering them to leverage AWS for their cloud computing needs.

**Prerequisites:**
●	AWS Academy Account (With learners lab enrolled)
●	Basic Understanding of Cloud Concepts
●	Internet Access
●	Web Browser

**Theory:**
AWS (Amazon Web Services) provides a scalable and flexible cloud computing platform that enables users to deploy, manage, and scale applications and services. Key components of AWS covered in this lab include:
●	EC2 (Elastic Compute Cloud): EC2 allows users to create virtual servers, known as instances, that can run applications, perform computations, and handle web traffic. EC2 offers a variety of instance types, tailored for different use cases, such as compute-intensive tasks or memory-optimized applications.
●	S3 (Simple Storage Service): S3 is an object storage service designed to store and retrieve any amount of data, at any time, from anywhere on the web. It provides high durability, availability, and scalability, making it ideal for storing large amounts of data, such as backups, archives, and media files.

Materials and Equipment:
●	Stable Internet Connection
●	AWS Academy Account
●	Web Browser

**Procedure:**
1. AWS Instance Creation
1.	Log in to AWS Academy Learner Lab:
○	Access the AWS Academy Learner Lab through your learning platform.
○	Sign in using your AWS Academy credentials. 
2.	Navigate to EC2 Dashboard:
○	Once in the AWS Management Console, search for "EC2" and select it to open the EC2 dashboard.
3.	Launch a New Instance:
○	Click on "Launch Instance."
○	Select an Amazon Machine Image (AMI) that suits your requirements (e.g., Amazon Linux 2, Ubuntu).
○	Choose the appropriate instance type based on your lab requirements.
○	Configure instance settings such as network, IAM roles, and monitoring.
○	Configure the security group to manage traffic rules.
○	Review and launch the instance, ensuring you select the appropriate key pair for secure access.
4.	Connect to the Instance:
○	After launching, select your instance in the EC2 dashboard.
○	Use the "Connect" option and follow the prompts to SSH into the instance using the key pair.
2. AWS S3 Object Storage
1.	Access S3 Service:
○	From the AWS Management Console, search for "S3" and open the S3 dashboard.
2.	Create a New S3 Bucket:
○	Click on "Create bucket."
○	Provide a unique name for the bucket and select a region.
○	Configure settings like versioning, encryption, and access permissions.
○	Review the settings and create the bucket.
3.	Upload Objects to S3 Bucket:
○	Select your newly created bucket.
○	Click on "Upload" and choose the files or folders you want to store.
○	Configure permissions and properties as needed.
○	Start the upload process.
![image](https://github.com/user-attachments/assets/43320ed8-9855-4f14-9426-f69969f5f0cc)
![image](https://github.com/user-attachments/assets/69074e1c-0554-4841-902e-6fe5507951ee)

**Expected Output:**
1. AWS Instance Creation
The new EC2 instance should appear in the EC2 dashboard with a "running" status. You should be able to view the instance details, including type, AMI, and public IP. SSH access to the instance should be functional.
2. AWS S3 Object Storage
The S3 bucket should be visible in the S3 dashboard. Uploaded files or folders will be accessible within the bucket. You should be able to manage and organize objects as needed.

Observations:

During the AWS lab, observe the details of the EC2 instance, including instance type and connectivity options, and note any challenges in establishing SSH access. For the S3 object storage, monitor the bucket creation process, including default settings, and evaluate the efficiency of file uploads and management. Pay attention to any issues with permissions or data access.

**Result:**
An EC2 instance and a S3 bucket was successfully created 

