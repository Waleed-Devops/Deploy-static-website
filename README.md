# Deploy a static website on Amazone S3
Amazon S3 (Simple Storage Service) is a highly scalable, reliable, and low-latency data storage infrastructure offered by Amazon Web Services (AWS). Here are the key points:

### Key Features:
###### Object Storage:
###### Storage of Objects: 
###### Scalability:
###### Elastic Scaling: 
###### Durability and Availability:
###### High Durability: 
###### High Availability:
###### Security:
###### Data Encryption: 
###### Access Control: 
###### Cost-Effective:
###### Pay-As-You-Go: 
###### Versioning: 
###### Accessibility:
###### Global Access: 


## Create a bucket in Amazon S3
- In the AWS Management Console, search for `S3
 - Choose  `Create bucket`.
-   `AWS Region`: select the Region closest to you.
-   For  `Bucket name`, enter  `Julian-Turner-website`. Make sure to replace  _name_  with your name.

![Screenshot_15-7-2024_18328_us-east-1 console aws amazon com](https://github.com/user-attachments/assets/cdf5b215-e283-40dd-9ab4-4d8efb2c954d)


![Screenshot_15-7-2024_183135_us-east-1 console aws amazon com](https://github.com/user-attachments/assets/e92d8949-bd69-420c-a9d1-ae0d353fbb5a)

![image](https://github.com/user-attachments/assets/4b12407f-c752-4451-aaef-74b9f265ef2f)

-General purpose :
Recommended for most use cases and access patterns. General purpose buckets are the original S3 bucket type. They allow a mix of storage classes that redundantly store objects across multiple Availability Zones.

![image](https://github.com/user-attachments/assets/c7d6a1eb-0af3-48a9-9ebd-dae17af5a31d)

- For Object Ownership, choose ACLs enabled.
- Choose Bucket owner preferred.


![image](https://github.com/user-attachments/assets/4a448cde-6d82-4134-8108-6a77f10b289a)

- For Block Public Access settings for this bucket, clear the check box for Block all public access.

  ![image](https://github.com/user-attachments/assets/618819af-0a1c-4c62-a43b-5d0fb624ecdc)
  
- Check the box that says “I acknowledge that the current settings might result in this bucket and the objects within becoming public.”
- For Bucket Versioning, choose Enable.

  ![image](https://github.com/user-attachments/assets/3aaf7b96-e06b-4100-a5ae-57288f3a9af5)

- Choose Create bucket.
- 
![image](https://github.com/user-attachments/assets/740bd3d5-edfc-4a05-a140-166feaa954b1)

- just created an S3 bucket!
- 
## Upload website content to your bucket

- Upload these files into your bucket (right click on each link, and select Save link as...):
  ![image](https://github.com/user-attachments/assets/2395bf88-9291-4ad0-9645-5a2c7918b9ba)






