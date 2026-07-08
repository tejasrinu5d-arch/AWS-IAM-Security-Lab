\# AWS IAM Security Lab Report



\## Introduction



The objective of this project was to understand how Amazon EC2 securely accesses AWS services using IAM Roles instead of long-term IAM User Access Keys.



\---



\## Tasks Performed



\- Created an IAM Role for Amazon EC2

\- Attached AmazonS3ReadOnlyAccess policy

\- Attached the IAM Role to an EC2 instance

\- Verified temporary credentials using AWS STS

\- Listed Amazon S3 buckets using the IAM Role

\- Demonstrated secure authentication without Access Keys

\- Verified Principle of Least Privilege



\---



\## Security Best Practices



\- No hardcoded AWS Access Keys

\- Temporary STS credentials

\- IAM Role authentication

\- Least Privilege permissions

\- Secure EC2 access



\---



\## Conclusion



This project demonstrates secure authentication between Amazon EC2 and AWS services using IAM Roles, Instance Profiles, and temporary credentials. The implementation follows AWS security best practices and avoids the use of long-term credentials.

