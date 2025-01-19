# Web Hosting

## 🌍 Overview
This project demonstrates how to host a Website using AWS. The goal is to use S3 to store the files and host the website on cloud.

## 🏗️ Architecture
<img src="s3-architecture.png" alt="drawing" width="500"/>

## 🥪 Prerequisites
- AWS Account
- IAM user with sufficient permissions
- Amazon S3
  
## 🧱 Setup Instructions

### Step 1: Create an S3 Bucket
1. Log in to your AWS Management Console.
2. Navigate to the S3 service.
3. Click on "Create bucket" and follow the prompts to create a new bucket.

### Step 2: Upload the files
1. Navigate to the bucket.
2. Upload "index.html" and the folder "NextWork - Everyone should be in a job they love_files".
3. Refresh the page and verify if the files were uplodaded correctly.

### Step 3: Enable Static Website Hosting
1. Go to properties tab of the S3 bucket.
2. Enable Static Website Hosting.
3. Visit the URL generated for the website.


## 🛠️ Configuration Details

### S3 Bucket Configuration
- Bucket Name: `example-bucket`
- Public Access: Enabled
- Static Website Hosting: Enabled

## 🚨 Troubleshooting

### Common Issues
- **Issue 1:** Unable to access S3 bucket.
  - **Solution:** Check the bucket's public access settings and ensure the bucket policy allows public access.

- **Issue 2:** 403 forbidden error
  - **Solution:** Modify the ACL rules and double check the files uploaded. Visit this [link](https://community.nextwork.org/c/i-have-a-question/project-1-troubleshooting-index-html?automatic_login=true) for troubleshooting common errors.

## 🔗 Additional Resources
- [AWS S3 Documentation](https://docs.aws.amazon.com/s3/)
- [AWS IAM Documentation](https://docs.aws.amazon.com/iam/)

