# 🚀 My Cloud Engineering Portfolio (Serverless AWS Architecture)

## 🌐 Live Website: [https://d2wzfn8f9c4zw5.cloudfront.net/index.html)

## 📋 Project Overview
This repository contains the frontend source code and backend architectural integration details of my personal Cloud Engineering Portfolio. More than just a static website, this portfolio is a fully functional **serverless web application** hosted on AWS. It showcases my ability to integrate frontend interfaces with powerful AWS cloud services, including an AI-powered chatbot and secure serverless APIs.

## 🏗️ Core AWS Integrations & Features

### 1. Serverless Hosting & Global CDN (Amazon S3 + CloudFront)
- The entire website is hosted purely on an **Amazon S3** private bucket.
- Delivered globally with low latency and high security using **Amazon CloudFront (CDN)**.
- **Origin Access Control (OAC)** is enforced to block direct public access to the S3 bucket.

### 2. Intelligent AI Chatbot (Amazon Lex)
- Integrated a conversational AI chatbot powered by **Amazon Lex**.
- The bot handles visitor queries dynamically, providing an interactive and automated user experience without requiring backend servers.

### 3. Secure Resume Delivery System (API Gateway + AWS Lambda)
- Integrated a secure document sharing workflow directly into the portfolio.
- When a recruiter requests my resume, the frontend calls a secure **Amazon API Gateway** endpoint.
- An **AWS Lambda** function processes the request and generates a time-limited (48-hour) pre-signed S3 URL, delivering the resume securely via email (Amazon SES).

## 🛠️ Tech Stack
- **Cloud Infrastructure:** AWS (S3, CloudFront, Lambda, API Gateway, DynamoDB)
- **AI / Machine Learning:** Amazon Lex
- **Frontend Technologies:** HTML5, CSS3, JavaScript, Bootstrap (Craftivo UI Base)
- **Security:** IAM Roles, Least-Privilege Policies, Origin Access Control (OAC), HTTPS/SSL

## 📂 Repository Structure
- `index.html`: Main landing page featuring the Amazon Lex chatbot integration.
- `project-*.html`: Detailed documentation and architecture diagrams for my 10+ cloud engineering projects.
- `assets/`: Contains optimized images, architecture diagrams, and CSS files.
- `fixed_lambda_handler.py`: Backend Python logic used for serverless integrations.

## 💡 Why This Portfolio Matters
Building this portfolio allowed me to treat my own professional identity as an enterprise-grade cloud project. It demonstrates my practical expertise in designing serverless architectures, integrating AWS AI services, enforcing strict cloud security, and automating content delivery on a global scale.
