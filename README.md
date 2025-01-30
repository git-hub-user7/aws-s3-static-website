# 🔒 Hosting a Static Website on AWS S3 with HTTPS

[![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com)
[![HTTPS](https://img.shields.io/badge/HTTPS-009688?style=for-the-badge&logo=letsencrypt&logoColor=white)](https://en.wikipedia.org/wiki/HTTPS)

A secure static website hosted on AWS S3 and served via AWS CloudFront with HTTPS. Built as part of my journey to learn cloud infrastructure.

## 🌐 Live Demo  
[Click here to view the secure website](https://d3ixzdcla3y4p.cloudfront.net/)  

## 🚀 Features  
- **HTTPS Encryption**: Secured using AWS CloudFront.  
- **Cost Optimization**: Free-tier compliant (AWS S3 + CloudFront).  
- **Security**: S3 access restricted to CloudFront only.  

## 📸 Screenshots  

### 1. S3 Bucket Static Website Hosting  
![S3 Static Hosting](assets/(1) S3 Website Hosting Settings.png)  
*Enabled static website hosting for the S3 bucket.*  

### 2. CloudFront Distribution Settings  
![CloudFront Settings](assets/(4) CloudFront Distibution Origin Access.png)  
*Configured CloudFront to redirect HTTP to HTTPS.*  

### 3. Secure Website Demo  
![Secure Website](assets/(5) HTTPS Secure Website.png)  
*Website loaded with HTTPS and a valid SSL certificate.*  

### 4. S3 Bucket Policy  
![Bucket Policy](assets/(2) S3 Access Blocking for CloudFront.png)  
*Restricted S3 access to CloudFront using a bucket policy.*  

## 🛠️ Technologies Used  
- **AWS S3**: Hosting static files.  
- **AWS CloudFront**: CDN with HTTPS.  
- **IAM Policies**: Securing S3 access.  

## 🔧 How to Run Locally  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/git-hub-user7/aws-s3-static-website.git  
