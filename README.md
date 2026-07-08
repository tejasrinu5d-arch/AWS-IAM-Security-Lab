\# AWS IAM Security Lab



\## Project Overview



This project demonstrates AWS Identity and Access Management (IAM) best practices by securely granting an Amazon EC2 instance access to AWS services using IAM Roles instead of long-term access keys.



The project covers IAM Roles, Instance Profiles, AWS Security Token Service (STS), temporary credentials, and the Principle of Least Privilege.



\---



\## Objectives



\- Create an IAM Role for Amazon EC2

\- Understand Instance Profiles

\- Attach an IAM Role to an EC2 instance

\- Verify temporary credentials using AWS STS

\- Access Amazon S3 without configuring AWS access keys

\- Demonstrate the Principle of Least Privilege



\---



\## Technologies Used



\- AWS IAM

\- Amazon EC2

\- AWS STS

\- Amazon S3

\- AWS CLI

\- Amazon Linux 2023

\- SSH



\---



\## Architecture



See:



architecture/IAM Architecture.png



\---



\## Project Workflow



1\. Created an IAM Role for EC2

2\. Attached AmazonS3ReadOnlyAccess policy

3\. Attached the role to the running EC2 instance

4\. Verified temporary credentials using AWS STS

5\. Accessed Amazon S3 without Access Keys

6\. Demonstrated Least Privilege permissions



\---



\## Learning Outcomes



\- IAM Roles

\- Instance Profiles

\- Temporary Credentials

\- AWS STS

\- EC2 Authentication

\- Secure AWS Access

\- Least Privilege



\---



\## Author



Teja Srinu

