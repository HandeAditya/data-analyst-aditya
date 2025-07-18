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

![image](https://github.com/user-attachments/assets/c4a5acba-3756-4dad-b045-518bb6faebce)

Security Group Configuration

![image](https://github.com/user-attachments/assets/4e2e9eb0-d236-43e7-953c-5bd5f2b2982a)

VPC Architecture

![image](https://github.com/user-attachments/assets/d49b3d47-fc75-4256-ba70-2968bf198a20)

Tools and Technologies

AWS (Amazon Web Services) – EC2, S3, VPC
Microsoft Excel – For planning and organizing the data lake
Draw.io – To create system diagrams
Fishbone Diagram – To find root causes of the discrepancy issues

Deliverables

A working cloud system on AWS for the Finance team
A planned and organized data lake in Excel
Diagrams showing system structure and data flow
Setup of AWS components like VPC, EC2, and S3
A final report with insights and recommendations
A presentation for the stakeholders

Summary

This project helped the Finance team move from outdated systems to a secure and modern cloud setup. With AWS, they can now store and use their financial data more efficiently, make better audit discrepancies , and detect the patterns. This setup is ready for future improvements like automation and live dashboards.

AWS Project 2 - Data Cleaning with AWS Glue DataBrew and S3

This project focuses on cleaning and organizing financial datasets using AWS Glue DataBrew and storing the outputs in a well-structured Amazon S3 bucket. It also involved reviewing AWS billing usage to manage cloud costs more effectively. The cleaned data is now ready for analysis and reporting.

Project Description
The goal of this project was to clean raw financial datasets using AWS Glue DataBrew and store them in a clean and accessible format on Amazon S3. The work also included monitoring AWS billing to ensure the infrastructure remained cost-efficient.

Objective
To prepare financial datasets for analysis by:

Reviewing and understanding cloud service billing
Cleaning data using Glue DataBrew recipes
Organizing cleaned datasets in a structured S3 storage layout

Dataset

The project focused on three key datasets: 

Audit Logs
Transaction Records
Account Reconciliations

Each dataset had formatting issues, null values, and inconsistencies that were addressed using AWS Glue DataBrew.

Methodology

1.AWS Billing Review

Started by checking the AWS Billing Dashboard to review service usage and costs from the previous week. This helped understand how resources were being consumed and how to manage them more efficiently going forward.

Billing Screenshot

![image](https://github.com/user-attachments/assets/db6c303c-71d6-445c-a237-b43acc539b75)

2. S3 Bucket Setup

Created a new S3 bucket named finance-cln-adi. Two main folders were added:

system/ – for internal datasets used by backend systems
user/ – for datasets used by end users or teams

This folder structure helped organize the outputs from each dataset type.

S3 Folder Structure

Audit Logs:

![image](https://github.com/user-attachments/assets/78e87b12-0647-4e18-8c2c-735376a691d6)

Account Reconciliations:

![image](https://github.com/user-attachments/assets/ea5178a3-e37e-4659-ae66-d850bde52bf0)

Transaction Records:

![image](https://github.com/user-attachments/assets/2b9436e4-0db3-444c-82f9-bc1777f17cbd)


3. Glue DataBrew Projects

Setup separate DataBrew Projects for each dataset:

Audit Logs
Account Reconciliations
Transaction Records

Each project allowed for visual data exploration and cleaning without writing code. Common tasks included:

Removing null values
Fixing column formats
Applying consistent field naming


DataBrew Interface Screenshots

Audit Logs:

![image](https://github.com/user-attachments/assets/9dfa388c-c98e-4006-a96a-e180122752f3)

Account Reconciliations:

![image](https://github.com/user-attachments/assets/912d7e41-4584-4f3c-b878-9b3e93d1f1fc)

Transaction Records:

![image](https://github.com/user-attachments/assets/3b0d4cdb-975c-4076-a40e-f6926aeedafa)

4. Running Data Cleaning Jobs
After finalizing the cleaning steps (called "recipes" in Glue DataBrew), I ran the jobs. The cleaned outputs were automatically saved into the correct folders in the S3 bucket:

system/Audit Logs/
system/Account Reconciliations/
system/Transaction Records/
user/Audit Logs/
user/Account Reconciliations/
user/Transaction Records/

Job Output Confirmation

![image](https://github.com/user-attachments/assets/3265d7cd-02f8-4016-84b0-3258d750c5c7)

Tools and Technologies
AWS Glue DataBrew – for no-code data cleaning
Amazon S3 – for organizing and storing cleaned datasets
AWS Billing Dashboard – for monitoring and managing costs

Key Learnings

Learned how to use AWS Glue DataBrew for practical data transformation
Improved ability to plan and structure cloud storage
Gained insights into AWS cost monitoring and budgeting
Built a simple end-to-end cleaning pipeline ready for integration into analytics workflows

Summary

This project shows how cloud-native tools like AWS Glue DataBrew and S3 can be used together to clean and manage financial data. It also highlights the importance of organizing datasets and keeping track of AWS usage to avoid unnecessary costs. The result is a structured, clean, and cost-managed dataset environment that’s ready for reporting and future analysis.


AWS Project 3 – Building a Scalable Budget Forecasting and Cost Monitoring System

This project demonstrates how I built a complete AWS cloud pipeline for organizing, processing, and analyzing budget data. The goal was to clean, prepare, store, and query historical budget records, and enable real-time insights with billing alerts.

Project Objective

To help an organization streamline their budget analysis and monitoring efforts using AWS Glue, DataBrew, Athena, S3, and CloudWatch. The project uses a cloud-native architecture to handle raw datasets, transform them, and store them in a query-ready format.

Key Steps and Activities

1. Data Lake Setup with Amazon S3

Uploaded Transaction records data into Amazon S3
Created multiple S3 buckets for raw, cleaned, and curated data
Used structured folders and descriptive naming

![image](https://github.com/user-attachments/assets/6d1f81fa-a9f8-45f3-8c89-458842953b72)

2. AWS Glue Data Catalog Configuration

Created a Data Catalog using AWS Glue
Registered tables with accurate metadata
Ensured schema recognition for further transformation

![image](https://github.com/user-attachments/assets/969bbe9f-ca91-4605-92ae-78e3fcb9b399)

3. Visual ETL Using AWS Glue DtaBrew

Used DataBrew to visually clean and transform datasets
Merged multiple sources like Audir logs, Transaction Records, Account Reconciliations.
Set up transformations like removing nulls, converting types, etc.

![image](https://github.com/user-attachments/assets/8c96e905-aed5-4fb7-b33f-cd919c44187e)

4. Querying with Amazon Athena

Queried joined datasets using Athena for insights
Previewed schema and validated transformation accuracy
Used SQL to extract cost patterns and department analysis

![image](https://github.com/user-attachments/assets/e47e350f-e130-4aeb-87b3-5ce4db763b02)

5. Budget Cost Monitoring and Alerts

Set up billing alerts using CloudWatch
Created alarm conditions for estimated charges exceeding threshold
Used alarm metrics to notify users

![image](https://github.com/user-attachments/assets/1f05c74a-a153-48c5-9b2c-935975cb6e73)

Cost Estimate

Estimated cost was generated using the AWS Pricing Calculator. Based on Glue sessions and usage pattern, the projected monthly cost was minimal.

![image](https://github.com/user-attachments/assets/55db4936-b02c-43ca-b0b3-b92ef613a959)

Final Architecture Diagram

An architecture diagram showing the complete flow—from ingestion to storage, transformation, and query.

![image](https://github.com/user-attachments/assets/638c0620-b372-4296-95b4-9f9bb3d6eb58)

Tools Used

Amazon S3 – Storage buckets for raw and curated data
AWS Glue – Data catalog and schema registry
AWS Glue DataBrew – Visual ETL tool for transformation
Amazon Athena – SQL queries on transformed data
Amazon CloudWatch – Billing alerts and monitoring

Summary

With this AWS setup, the finance team can now analyze discrepancy in the Audit Logs, track Transaction Records, and Account Reconciliations overdues.. The modular ETL process makes updates simple and ensures future datasets can be integrated easily.
