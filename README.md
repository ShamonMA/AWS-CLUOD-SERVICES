# AWS Cloud Architecture & Process Blueprints

This repository serves as a professional portfolio of architectural diagrams and step-by-step process flows for AWS cloud services. These blueprints demonstrate advanced implementation patterns for serverless compute, event-driven messaging, relational databases, and automated CI/CD pipelines.

---

## 🏗️ Architectural Workflows

### 1. Amazon SNS Setup Guide
A comprehensive 4-module process flow covering the end-to-end configuration of Amazon SNS. It details topic creation via the Console or CLI, subscription management across multiple protocols (Email, Lambda, HTTP/S), and message publishing workflows.

**Process Flow:**
![Amazon SNS Setup Guide](SNS%20Configuration%20Roadmap.jpg)

---

### 2. AWS RDS SQL Server: S3 Backup & Restore
A technical operational workflow detailing the one-time configuration of IAM roles and option groups, followed by the specific SQL commands required to execute and monitor database restores from an Amazon S3 bucket.

**Process Flow:**
![AWS RDS SQL Server Backup & Restore](RDS%20db%20restore%20from%20s3%20bucket.jpg)

---

### 3. AWS Lambda Function Creation (.NET C#)
A step-by-step developer guide for deploying .NET C# applications from Visual Studio to AWS Lambda. This covers the installation of the AWS Toolkit, IAM role execution policies, and the final deployment verification process.

**Process Flow:**
![AWS Lambda Function Creation](Lambdafunction_configuration.jpg)

---

### 4. AWS Lambda to SNS Email Setup (VPC-Bound)
A specialized networking blueprint for triggering email notifications via SNS from a Lambda function residing within a private VPC. It includes configurations for VPC Interface Endpoints, IAM inline policies, and C# code implementation.

**Process Flow:**
![AWS Lambda to SNS Email Setup](Send%20mail%20using%20SNS%20from%20Lambda.jpg)

---

### 5. EC2 to CloudWatch Logging Workflow
A step-by-step configuration flow for centralized logging. This diagram outlines the process of creating IAM roles, installing the CloudWatch Agent via RDP on Windows instances, and verifying log population within CloudWatch Log Groups.

**Process Flow:**
![EC2 to CloudWatch Logging](EC2-to-CloudWatch-Logging-Workflow.jpg)

---

### 6. CloudWatch EC2 CPU Alarm Setup
An observability blueprint for proactive infrastructure monitoring. It details the process of defining metric conditions, configuring SNS notification triggers, and performing CPU stress testing to verify alarm functionality.

**Process Flow:**
![CloudWatch EC2 CPU Alarm](CloudWatch-EC2-Alarm.jpg)

---

### 7. Docker CI/CD Pipeline (GitLab & ECS)
An advanced orchestration blueprint for containerized .NET APIs. This flow demonstrates the integration of GitLab source control with AWS CodeBuild, Amazon ECR for image storage, and Amazon ECS Fargate for automated application deployment.

**Process Flow:**
![Docker CI/CD Pipeline](Docker-CI&CD.jpg)

---

### 8. CI/CD Steps: AWS CodePipeline & CodeDeploy
A multi-stage deployment strategy for .NET 8 APIs onto Windows Server environments. It highlights the coordination between S3 artifacts, GitLab connections, and the AWS CodeDeploy agent for in-place application updates.

**Process Flow:**
![AWS CodeDeploy Flow](CI_CD%20Steps%20-%20AWS-Codebuild-Codedploy-Codepipeline.jpg)

---

## 🛠️ Tech Stack Featured
*   **Development:** .NET 8 / C#, Visual Studio, PowerShell.
*   **Cloud Infrastructure:** AWS (Lambda, SNS, RDS, EC2, S3, CloudWatch).
*   **DevOps & Containers:** Docker, GitLab, Amazon ECR/ECS, AWS CodePipeline.
*   **Networking:** VPC Endpoints, IAM Policy Management.
