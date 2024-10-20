# 🚀 AWS S3 Website Hosting Project
This project showcases how to host a static website using Amazon S3, from bucket creation to configuring it for public access.
_________________________________________________________________________________________________________________________________
📋 Project Summary
Service Used: Amazon S3 (Simple Storage Service)
Region: Europe (London) – eu-west-2
Files Hosted: HTML and image assets
_________________________________________________________________________________________________________________________________
⚙️ Steps to Complete
Create S3 Bucket

The bucket name was globally unique, ensuring no conflicts.
Region: London (eu-west-2) for low-latency access.

![screenshot of bucket created](images/screenshot 2024-10-19 111038.png)

Upload Website Files

Uploaded index.html and image files to the S3 bucket.

Enable Static Website Hosting

Configured static website hosting by setting the index and error documents.

Set Bucket Permissions

Edited the Access Control List (ACL) to allow public read access.
_________________________________________________________________________________________________________________________________
🔧 Challenges & Solutions
Error: Initially, objects were private by default.
Solution: Adjusted the bucket policy to allow public access.


