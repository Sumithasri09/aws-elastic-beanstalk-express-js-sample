# Continuous Delivery Pipeline with AWS

This project demonstrates a complete Continuous Delivery (CD) pipeline for a sample web application using AWS services and GitHub.

## 🛠️ Prerequisites

Before you begin, ensure you have:

- An AWS account
- A GitHub account
- Git installed on your local machine

---

## 📦 Module 1: Set Up Git Repository

- Fork the source GitHub repository to your own account
- Store all application code and metadata in the new GitHub repo
- Use Git commands to manage your codebase

---

## 🚀 Module 2: Deploy Web App

- Configure an AWS Elastic Beanstalk environment
- Deploy the sample web application to Beanstalk
- Verify the web app is running successfully

---

## 🔧 Module 3: Create Build Project

- Set up an AWS CodeBuild project
- Configure GitHub as the source for the build
- Run an initial build to ensure your project compiles and packages correctly

---

## 🔁 Module 4: Create Delivery Pipeline

- Create an AWS CodePipeline pipeline
- Add **Source Stage** connected to your GitHub repository
- Add **Build Stage** using AWS CodeBuild
- Add **Deploy Stage** to deploy the app to Elastic Beanstalk

---

## ✅ Module 5: Finalize and Test Pipeline

- Add a **Manual Approval** step before the Deploy stage
- Review and approve changes manually before deployment to production

---

## 🎉 Result

After completing this pipeline, any changes pushed to your GitHub repo will trigger an automated flow that builds, reviews, and deploys your app to AWS Elastic Beanstalk.

---



