**Title:** Understand the working of AWS - Create AWS-Instance Creation, AWS-S3-ObjStorage

**Objective:**
The objective of this lab is to provide a comprehensive understanding of how to
work with key AWS services, specifically focusing on the creation of EC2 instances
and managing object storage using AWS S3. By the end of this experiment,
participants will have a clear understanding of the step-by-step processes involved
in setting up a virtual server (EC2 instance) and storing data securely and
efficiently using S3, empowering them to leverage AWS for their cloud computing
needs.

**Prerequisites:**
● Basic Understanding of Cloud Concepts
● Internet Access
● Web Browser
Theory:
AWS (Amazon Web Services) provides a scalable and flexible cloud computing
platform that enables users to deploy, manage, and scale applications and services.
Key components of AWS covered in this lab include:
● **EC2 (Elastic Compute Cloud):** EC2 allows users to create virtual servers,
known as instances, that can run applications, perform computations, and
handle web traffic. EC2 offers a variety of instance types, tailored for
different use cases, such as compute-intensive tasks or memory-optimized
applications.
● S3 **(Simple Storage Service):** S3 is an object storage service designed to
store and retrieve any amount of data, at any time, from anywhere on the
web. It provides high durability, availability, and scalability, making it ideal
for storing large amounts of data, such as backups, archives, and media files.
Materials and Equipment:
● Stable Internet Connection
● AWS Academy Account
● Web Browser

**Procedure:**
1. **AWS Instance Creation**
 1. Log in to AWS Academy Learner Lab:
 ○ Create a free tier AWS account and save your root user email
 ○ Sign in using your credentials.
 ![image](https://github.com/user-attachments/assets/513b4ac3-3a8a-4fc7-a284-60285ddb511e)
 ![image](https://github.com/user-attachments/assets/13a8112d-e1d2-4fa0-a608-7449b39367cf)

 2. Navigate to EC2 Dashboard:
 ○ Once in the AWS Management Console, search for "EC2" and select it to open the EC2 dashboard.
 ![image](https://github.com/user-attachments/assets/31a4794a-1c75-45cd-9304-759736a1eb02)

 3. Launch a New Instance:
 ○ Click on "Launch Instance."
 ○ Select an Amazon Machine Image (AMI) that suits your requirements(e.g., Amazon Linux 2, Ubuntu).
 ○ Choose the appropriate instance type based on your lab requirements.
 ○ Configure instance settings such as network, IAM roles, and monitoring.
 ○ Configure the security group to manage traffic rules.
 ○ Review and launch the instance, ensuring you select the appropriate key pair for secure access.
 ![image](https://github.com/user-attachments/assets/aa835502-e853-4d65-9ee4-2f1b2c2215e8)
 ![image](https://github.com/user-attachments/assets/ea0b9bcd-a57e-4d8f-809a-6d2a61137561)
 ![image](https://github.com/user-attachments/assets/7c51590c-68b1-4831-9eda-49e6be678cb5)

 4. Connect to the Instance:
 ○ After launching, select your instance in the EC2 dashboard.
 ○ Use the "Connect" option and follow the prompts to SSH into the instance using the key pair.
 ![image](https://github.com/user-attachments/assets/9df7e470-0f12-40ba-b868-79ec36b5bf5c)

 5. Stop and Terminate the running Instance:
 o Once after connecting to the EC2 instance, ensure that the instance is stopped and terminated to avoid it running and incurring AWS charges.
 ![image](https://github.com/user-attachments/assets/54cd64f0-8997-49eb-a489-9ba310a592fa)
 ![image](https://github.com/user-attachments/assets/c2eb9df6-0637-4032-bc11-5eed7ad6a3d8)

2. **AWS S3 Object Storage**
 1. Access S3 Service:
 ○ From the AWS Management Console, search for "S3" and open the S3 dashboard.
 ![image](https://github.com/user-attachments/assets/bfe180bc-0aa2-4fc2-ad47-0fd13a470ba9)

 2. Create a New S3 Bucket:
 ○ Click on "Create bucket."
 ○ Provide a unique name for the bucket and select a region.
 ○ Configure settings like versioning, encryption, and access permissions.
 ○ Review the settings and create the bucket.
 ![image](https://github.com/user-attachments/assets/be5e57f6-c374-4fe9-9e69-759e050b0f18)

 3. Upload Objects to S3 Bucket:
 ○ Select your newly created bucket.
 ○ Click on "Upload" and choose the files or folders you want to store.
 ○ Configure permissions and properties as needed.
 ○ Start the upload process.
 ![image](https://github.com/user-attachments/assets/21a43fcd-82bd-4af4-af5b-af2e0ccc0ab3)

 4: Open the uploaded file in the browser
 ○ Select your newly uploaded file.
 ○ Click on "Open”
 ○ You can view the file in the browser successfully now
 ![image](https://github.com/user-attachments/assets/c5b2dd0c-dba4-4421-a544-d8f9726b6a47)

 5: Delete the uploaded file and S3 bucket after use
 ○ Select your newly uploaded file.
 ○ Click on "Delete”
 ○ You can see the uploaded file is deleted successfully
 ○ Select the created S3 bucket, click on “Delete”
 ○ You can see the created S3 bucket is deleted successfully
 ![image](https://github.com/user-attachments/assets/acc13474-4e51-48ab-a671-08de82f0d19e)

**Expected Output:**
1. AWS Instance Creation
The new EC2 instance should appear in the EC2 dashboard with a "running" status.
You should be able to view the instance details, including type, AMI, and public IP.
SSH access to the instance should be functional.
2. AWS S3 Object Storage
The S3 bucket should be visible in the S3 dashboard. Uploaded files or folders will
be accessible within the bucket. You should be able to manage and organize objects
as needed.
Observations:
During the AWS lab, observe the details of the EC2 instance, including instance
type and connectivity options, and note any challenges in establishing SSH access.
For the S3 object storage, monitor the bucket creation process, including default
settings, and evaluate the efficiency of file uploads and management. Pay attention
to any issues with permissions or data access.
The instances and S3 buckets creation and deletion is observed and basic
understanding is obtained.
Result:
An EC2 instance and a S3 bucket was successfully created and deleted.
