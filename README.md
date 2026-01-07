# AWS Static Website Deployment — S3 + CloudFront + CloudFormation (IaC)

This project demonstrates how I deployed a **production-ready static website** on AWS using:
- **Amazon S3** — static website hosting  
- **AWS CloudFront** — HTTPS + global CDN  
- **AWS CloudFormation (YAML)** — full Infrastructure-as-Code deployment  
- **IAM + S3 Bucket Policies** — secure object access  

The goal of this project was to **build cloud deployment skills on real AWS services** while following best practices used in industry.

---

## 🚀 Live Architecture Preview

![Website Preview](assets/site-preview.png)

---

## 🏗 Architecture Overview

### 🔹 Amazon S3 — Website Hosting  
Stored and served static HTML/CSS content from an S3 bucket configured for static hosting.

### 🔹 AWS CloudFront — CDN + HTTPS  
Added CloudFront for:
✔ SSL / HTTPS  
✔ Global content distribution  
✔ Better latency & security  

![CloudFront](assets/cloudfront.png)

---

### 🔹 AWS CloudFormation — Infrastructure as Code (IaC)

I wrote a **YAML CloudFormation template** to automatically create:
✔ S3 bucket  
✔ Public bucket policy  
✔ Website hosting configuration  

This ensured the deployment was:
✔ Repeatable  
✔ Version-controlled  
✔ Automated  

![CloudFormation](assets/cloudformation.png)

---

### 🔹 IAM & S3 Bucket Policy — Secure Access

Configured bucket policy to allow **only website object read-access**, avoiding over-permission.

![S3 Bucket](assets/s3-bucket.png)

---

## 📊 Monitoring & Learning Outcomes

I used **CloudWatch / Console metrics** to understand:
- Request volume
- Cache hit ratio
- Latency behaviour

---

## ✔ Key Skills Practiced

- Deploying static websites on AWS
- Writing CloudFormation YAML
- Setting IAM & S3 bucket policies
- Enabling secure HTTPS using CloudFront
- Understanding production-style architecture

---

## 📁 Project Structure

