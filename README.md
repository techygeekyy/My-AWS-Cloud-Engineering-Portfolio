# 🌐 AWS Cloud Engineering Portfolio (Serverless Architecture)

## 🎥 Live Website & AI Chatbot Demonstration
Experience the fully functional serverless architecture and AI chatbot here:  
**[▶️ Visit My Live Portfolio](https://d2wzfn8f9c4zw5.cloudfront.net/index.html)** 

## 📋 Project Overview
This repository contains the frontend source code and backend architectural integration details of my personal Cloud Engineering Portfolio. More than just a static website, this portfolio is a fully functional **serverless web application** hosted on AWS. It showcases my ability to integrate frontend interfaces with powerful AWS cloud services, including an AI-powered chatbot and secure serverless APIs.

**Project Context:** Master Enterprise Cloud Portfolio  
**Environment:** Fully Managed Serverless AWS Architecture  
**Core Tech Stack:** AWS (S3, CloudFront, Lambda, API Gateway, DynamoDB), Amazon Lex, HTML5, CSS3, JavaScript, Python (Boto3)  

## 🎯 Objectives
- Deploy a highly secure, serverless cloud engineering portfolio.
- Host static assets securely using Amazon S3 and CloudFront (CDN).
- Integrate a conversational AI chatbot using Amazon Lex.
- Implement a secure, serverless resume delivery system using API Gateway and Lambda.
- Demonstrate real-world enterprise cloud deployment and security practices.

## 🌍 Environment Details
- ☁️ **Cloud Provider:** AWS
- ☁️ **Architecture Type:** Serverless Web Application
- ☁️ **Frontend Hosting:** Amazon S3 + Amazon CloudFront (OAC)
- ☁️ **Backend Compute:** AWS Lambda (Python)
- ☁️ **AI / Machine Learning:** Amazon Lex

## 🧱 Core Architecture & Integrations
- 🏗️ **Serverless Hosting & Global CDN:**
  - The entire website is hosted purely on an **Amazon S3** private bucket.
  - Delivered globally with low latency using **Amazon CloudFront (CDN)**.
  - **Origin Access Control (OAC)** is enforced to block direct public access to the S3 bucket.
- 🏗️ **Intelligent AI Chatbot (Amazon Lex):**
  - Integrated a conversational AI chatbot powered by **Amazon Lex**.
  - Handles visitor queries dynamically, providing an automated user experience without requiring backend servers.
- 🏗️ **Secure Resume Delivery System:**
  - **API Gateway** exposes a secure REST endpoint for the frontend.
  - **AWS Lambda** function validates the request and generates a 48-hour pre-signed S3 URL.
  - **Amazon SES** securely delivers the resume to the recruiter's email.
  - **Amazon DynamoDB** logs request metadata for auditing and tracking.

## 🔐 Security & Best Practices Implemented
- 🛡️ Strict IAM Roles and Least-Privilege Policies enforced across all services.
- 🛡️ Origin Access Control (OAC) successfully blocks direct S3 access.
- 🛡️ Complete serverless architecture eliminating traditional server vulnerabilities.
- 🛡️ Time-limited pre-signed URLs implemented for zero-trust document sharing.
- 🛡️ HTTPS/SSL encryption enforced for data in transit.

## 📂 Repository Structure
- `index.html`: Main landing page featuring the Amazon Lex chatbot integration.
- `project-*.html`: Detailed documentation and architecture diagrams for my 10+ cloud engineering projects.
- `assets/`: Contains optimized images, architecture diagrams, and CSS files.
- `fixed_lambda_handler.py`: Backend Python logic used for the secure resume delivery system.
- `assistant.json`: Configuration and design logic for the Amazon Lex AI Chatbot.

## 💡 Why This Portfolio Matters
Building this portfolio allowed me to treat my own professional identity as an enterprise-grade cloud project. It demonstrates my practical expertise in designing serverless architectures, integrating AWS AI services, enforcing strict cloud security, and automating content delivery on a global scale.
