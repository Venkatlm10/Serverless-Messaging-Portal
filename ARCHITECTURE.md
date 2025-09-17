# Serverless Messaging Portal 🚀

A fully serverless, scalable messaging portal built using AWS services. This project demonstrates how to architect a modern communication platform without managing servers—leveraging the power of AWS Lambda, API Gateway, S3, SES, SNS, and Step Functions.

## 🧰 Technologies Used

- **Amazon S3** – Static website hosting and file storage
- **Amazon SES** – Email notifications and messaging
- **Amazon SNS** – Push notifications and topic-based messaging
- **AWS Lambda** – Serverless backend logic
- **Amazon API Gateway** – RESTful API endpoints
- **AWS Step Functions** – Workflow orchestration
- **IAM** – Role-based access control and security

## 🌐 Architecture Overview

The portal is designed to handle user interactions via a hosted frontend (S3), trigger backend workflows (Lambda + Step Functions), and deliver messages through SES and SNS. API Gateway acts as the bridge between the frontend and backend services.

## 🚀 Features

- Send email and SMS notifications
- Trigger workflows based on user actions
- Fully serverless and event-driven
- Scalable and cost-efficient
- Hosted frontend via S3 static website

## 📦 Getting Started

1. Clone the repo  
   `git clone https://github.com/Venkatlm10/Serverless-Messaging-Portal.git`

2. Deploy resources using AWS Console or IaC tools (e.g., SAM, CloudFormation)

3. Configure IAM roles and permissions

4. Update SES/SNS settings with verified domains and phone numbers

5. Access the portal via the S3-hosted URL

## 📸 Live Demo

Check out the hosted version [here](http://venkii-api.s3-website.ap-south-1.amazonaws.com/)

## 🛡️ License

This project is licensed under the MIT License.

---

