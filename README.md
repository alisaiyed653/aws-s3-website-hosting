# 🚀 AWS S3 Website Hosting Project
This project showcases how to host a static website using Amazon S3, from bucket creation to configuring it for public access.
_________________________________________________________________________________________________________________________________

## 📋 Project Summary

Service Used: Amazon S3 (Simple Storage Service)
Region: Europe (London) – eu-west-2
Files Hosted: HTML and image assets
_________________________________________________________________________________________________________________________________
## ⚙️ Steps to Complete

- Create S3 Bucket

  The bucket name was globally unique, ensuring no conflicts.
  Region: London (eu-west-2) for low-latency access.

![Screenshot 2024-10-19 111038](https://github.com/user-attachments/assets/4c624ceb-1db3-4217-89df-8efdc29c7a5e)

- Upload Website Files

  Uploaded index.html and image files to the S3 bucket.

![Screenshot 2024-10-19 113759](https://github.com/user-attachments/assets/4a6e0318-3d5a-4750-9829-bb46c4d1bbbb)

- Enable Static Website Hosting

  Configured static website hosting by setting the index and error documents.

![Screenshot 2024-10-19 120920](https://github.com/user-attachments/assets/731a3458-db9d-467c-b93c-2f97015707c9)

- Set Bucket Permissions

  Edited the Access Control List (ACL) to allow public read access.
_________________________________________________________________________________________________________________________________
## 🔧 Challenges & Solutions

- Error: Initially, objects were private by default.
  As a result these were not being displayed

![Screenshot 2024-10-19 174358](https://github.com/user-attachments/assets/0d62c7db-53e0-4850-8ed1-b66dbcdc71b8)

- Solution: Adjusted the bucket policy to allow public access.

![Screenshot 2024-10-19 175418](https://github.com/user-attachments/assets/70f52b8a-0cc9-4705-ad8f-f315be74a8fa)



