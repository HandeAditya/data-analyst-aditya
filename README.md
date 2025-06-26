AWS Cloud Foundations – Learning Journey

This repository contains my notes and key takeaways from the AWS Cloud Foundations learning modules. Each section includes the key concepts I learned, labs I completed, and screenshots of knowledge check results and lab activities.

Module 1: Introduction to Cloud Concepts

In this module, I learned what cloud computing really means. I compared it to traditional computing and understood how cloud computing is more flexible, cost-effective, and scalable.

Key topics I learned:

The difference between On-Premise and Cloud Computing
Benefits of cloud: pay-as-you-go, scalability, global access
Introduction to IaaS, PaaS, and SaaS
Real-world examples of cloud usage
Knowledge Check:
Module 1 Knowledge Check
![image](https://github.com/user-attachments/assets/efe71b27-0274-4c8c-9a35-02cb3dff38d5)

Module 2: AWS Core Services & Tools

In this part, I explored the basic services provided by AWS and how they help businesses manage their applications and data in the cloud.

Key things I learned:

EC2: Launching virtual servers
S3: Storing files and objects
RDS: Handling databases in the cloud
AWS Pricing Calculator: To estimate service costs
How to find support using AWS Support Plans
Knowledge Check:
Module 2 Knowledge Check
![image](https://github.com/user-attachments/assets/c832c262-187d-4ae4-b5c5-b8ba1acc9038)

Module 3: Global Infrastructure & Networking

This module taught me how AWS works around the world using different Regions, Availability Zones, and Edge Locations.

I learned:

How AWS ensures availability through global infrastructure
The difference between a Region, AZ, and Edge Location
Why location of data centers matters for speed, privacy, and performance
Knowledge Check:
Module 3 Knowledge Check
![image](https://github.com/user-attachments/assets/e091322d-17fc-4fdc-b8d7-3eac8a9796ec)

Module 4: Security, Responsibility, and IAM

I learned how AWS keeps data secure and how security responsibilities are shared between AWS and users.

Key takeaways:

The Shared Responsibility Model
Creating and managing IAM users, groups, roles, and policies
Setting up Multi-Factor Authentication (MFA) for stronger security
Lab Activity:
Created IAM roles and configured security policies.
Module 4 Lab Screenshot

Knowledge Check:
Module 4 Knowledge Check
![image](https://github.com/user-attachments/assets/3560ee78-ddb0-40ee-98a9-64f2f437c578)

Module 5: VPC and Network Design

This module helped me create my own isolated network using Amazon VPC.

What I did:

Designed a Virtual Private Cloud with subnets, route tables, and gateways
Controlled traffic with Security Groups and Network ACLs
Built a secure and scalable architecture
Lab Activity:
Built and configured a full VPC environment.
Module 5 Lab Screenshot

Knowledge Check:
Module 5 Knowledge Check
![image](https://github.com/user-attachments/assets/9d27ea9b-5cd1-4c53-bb7e-d9e6d9c4b373)

Module 6: Serverless and AWS Lambda

In this module, I explored serverless computing using AWS Lambda, which allows running code without provisioning or managing servers.

Key learnings:

How Lambda works with events and triggers
Writing and deploying functions in the AWS Management Console
Example use cases to reduce cost and simplify development
Lab Activity:
Created and deployed Lambda functions.
Module 6 Lab Screenshot

Knowledge Check:
Module 6 Knowledge Check
![image](https://github.com/user-attachments/assets/452a5825-6155-4030-98bf-2dd382d2bbaa)

Module 7: Containers and Amazon ECR

This module introduced me to containers and Amazon ECR (Elastic Container Registry).

What I gained:

Understanding of container technology and how it's different from VMs
How to push and pull images using ECR
Deployment basics for containerized apps
Lab Activity:
Worked with container registries and uploaded images.
Module 7 Lab Screenshot

Knowledge Check:
Module 7 Knowledge Check
![image](https://github.com/user-attachments/assets/c1dd70ab-1248-48f5-b640-b9fcc7eed2e7)

Summary


These seven modules gave me a solid understanding of AWS fundamentals—from cloud concepts and core services to networking, security, serverless, and containers. The labs and knowledge checks helped reinforce what I learned, and I'm now confident in applying these skills in real-world cloud projects.




AWS Projects 

Welcome! This is a collection of my practical AWS projects and assignments. These projects focus on cloud computing, data storage, and AWS infrastructure.


Project 1 - Improving Budget Forecasting for the Finance Team Using AWS


Project Description

In this project, I helped the Finance Department fix problems in their audit discrepancies in financial reporting. I used AWS (Amazon Web Services) to build a cloud-based system that makes their data easier to manage, more secure, and more accurate for future use.

Objective

 The goal was to study where the finance team's currently lacking in the audits in reporting, then create a cloud solution using AWS tools like S3 and EC2 to organize and protect their financial data.


 Dataset

 I worked with different types of financial data and uploaded them into cloud storage:

 Audit Logs - Past audit logs report
 Transaction Records - Past transaction records update
 Account Reconciliations - Comparing sets of the records.

 Methodology

1. Data Collection and Preparation
Found out why there was the discrepancies in the audits using a Fishbone Diagram
Planned how the data would be organized using Excel
Uploaded clean and well-labeled data to AWS S3

2. Descriptive Statistics
Looked at trends in patterns in transactions and logs that lead to inconcistencies in audits
Grouped data by department and time
Found differences between discrepancies and actual patterns

3. Data Visualization
![image](https://github.com/user-attachments/assets/71af0497-3a16-40bb-bc16-edef9e123180)

4. Team Segmentation
Identified how different finance teams use data
Created strategies for giving the right access to the right people

5. Insights and Findings
Old systems couldn’t grow with the company
Data was scattered and hard to work with
AWS helped bring all financial data into one place and lower storage costs

6. Recommendations
Keep using AWS EC2 and S3 for better data handling
Use AWS Lambda to automate updates and refreshes

7. Implementation Screenshots

EC2 Instance Setup

![image](https://github.com/user-attachments/assets/aa9ffc9b-ff93-40e4-ba92-f89a4ae33e2f)

S3 Bucket Structure


