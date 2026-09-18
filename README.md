Week 7 Cloud Security Assessment

A professional evidence package for the Summer of Cybersecurity 2026 practical assignment at AstraQuantum Tech.

Student Information

•
Name: Muhammad Umer Imran

•
Student ID: AQT-1170

•
Instructor: Hazrat Umer

•
Focus: Cloud security, AWS IAM, Amazon S3, identity management, and access-control review

Repository Name

Recommended repository name: cloud-security-week7-assessment

Project Summary

This repository documents controlled cloud-security learning activities completed in authorized training environments. The work focuses on identifying excessive IAM permissions, reviewing S3 bucket and object exposure, and understanding how storage misconfiguration can lead to information disclosure.

Completed Activities

1. Intro to AWS IAM Enumeration

•
Platform: Pwned Labs

•
URL: https://app.pwnedlabs.io/labs/intro-to-aws-iam-enumeration

•
Focus: IAM identities, permissions, policy scope, and least privilege

2. AWS S3 Enumeration Basics

•
Platform: Pwned Labs

•
URL: https://app.pwnedlabs.io/labs/aws-s3-enumeration-basics

•
Focus: S3 buckets, objects, storage exposure, and access controls

3. FlAWS Challenge — Levels 1–2

•
Platform: FlAWS

•
URL: http://flaws.cloud/

•
Focus: Controlled demonstration of S3 information exposure and public-access risk

Key Security Lessons

The assessment demonstrates why cloud identities should receive only the permissions required for their tasks. It also shows why S3 storage should remain private by default and why public-access settings must be reviewed at both account and resource levels.

Recommended defensive controls include:

•
Least-privilege IAM policies.

•
Separation of duties and permissions-boundary review.

•
S3 Block Public Access.

•
Restrictive bucket and object policies.

•
Encryption and access logging.

•
Continuous monitoring for public exposure.

•
Removal of secrets and sensitive data from public artifacts.

Repository Structure

Plain Text


.
├── README.md
├── Cloud_Security_Assessment_Report.md
├── LinkedIn_Post.md
└── evidence/
    ├── iam/
    ├── s3/
    └── flaws/



Responsible-Use Notice

All activities were performed in authorized learning environments. This repository must not contain passwords, tokens, private keys, or confidential production data. The techniques and observations are intended for defensive learning and controlled assessment only.

Attribution

•
Program: Summer of Cybersecurity 2026

•
Company: AstraQuantum Tech

•
Instructor: Hazrat Umer

•
Student: Muhammad Umer Imran

