# EmployeeDirectoryAppOnAWS
# Project Done Apart of AWS Cloud Technical Essentials Course.

![employeedire](https://user-images.githubusercontent.com/97641116/197156034-4795ffc0-80f0-4d2d-b9f2-24ee787e68c9.PNG)

In this project we use a basic employee directory application to run through multiple AWS Cloud instance from creating roles, launching instances, setting up a VPC, creating S3 Bucket, setting up a DataBase, and Load Balancing and Auto Scaling.

# Creating EC2 Instance
Using the IAM role we create an Amazon Elastic Compute Cloud instance of the employee directory application.
![instancemade](https://user-images.githubusercontent.com/97641116/197154340-aff78a8f-0215-4a66-9f87-9b283322f6e3.PNG)

# Setting a VPC
Next we set up a virtual private cloud with two public subnets along with a private and public route table. We launch the instance inside this VPC.
![routetablemade](https://user-images.githubusercontent.com/97641116/197154657-f0649b7a-e0aa-4cd8-b6db-d4031b613126.PNG)

# Creating S3 Bucket
Following this we created an Amazon Simple Storage Service Bucket for the employee photos to be stored in.

# Created DynamoDB Table
Next we created a database to store the employees using the DynamoDB Table of AWS.
![createDatabaseusingDyanamo](https://user-images.githubusercontent.com/97641116/197155295-ffc1072c-f3f3-4a27-8f15-887b113bdfde.PNG)

After adding a user we can see the information stored in the database.
![userInDatabase](https://user-images.githubusercontent.com/97641116/197155317-bc9f62a4-195b-4a4a-9d1f-003ff47901a5.PNG)

# Load Balancing and Auto Scaling
Finally we finish off by setting an Elastic Load Balancing load balancer and Auto Scaling group that will scale the application horizontally.

Here we created the load balancer.
![loadbalancer](https://user-images.githubusercontent.com/97641116/197155720-fd57260d-4c37-48d4-8de0-2edb0bd37d13.PNG)

Next we created the launch template.
![createdtemplate](https://user-images.githubusercontent.com/97641116/197155827-1176ff12-f1aa-4068-956b-30cff3aa9b35.PNG)

Finally we have created the autoscaling group
![autoscaling](https://user-images.githubusercontent.com/97641116/197156006-1163fc7c-7dc9-44f4-9abb-88d77c4fd9a3.PNG)
