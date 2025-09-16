# Java Web Application with CI/CD Pipeline

This project documents my journey of building a CI/CD pipeline and deploying a Java web application in the cloud using AWS and GitHub. It covers setting up the app, managing dependencies, packaging, deploying, and automating CI/CD pipelines.

---

## Table of Contents

- [Introduction](#introduction)  
- [What I Did](#what-i-did)  
- [Setup](#setup)  
- [Dependencies](#dependencies)  
- [Steps](#steps)  
- [Conclusion](#conclusion)  

---

## Introduction

In this project, I aimed to take a simple web application and deploy it fully in the cloud. Along the way, I explored AWS services like **CodeArtifact**, **CodeBuild**, **CodeDeploy**, and **CodePipeline**, while integrating my GitHub repository for version control and CI/CD. This project demonstrates practical skills in cloud deployment and DevOps best practices.

---

## What I Did

This project showcases my experience with:

- Setting up a web app in AWS  
- Connecting GitHub with AWS  
- Managing dependencies with CodeArtifact  
- Packaging and deploying apps with CodeBuild and CodeDeploy  
- Automating CI/CD pipelines with CodePipeline  
- Optionally, defining infrastructure as code with CloudFormation  

---

## Setup

To get started with this project:

1. **Clone the repository**  
    ```bash
    git clone git@github.com:IsaMukadam/nw-web-project.git
    cd nw-web-project
    ```

2. **Configure AWS CLI**  
    ```bash
    aws configure
    ```
    Enter your AWS Access Key, Secret Key, region, and output format.

3. **Install project dependencies** (see [Dependencies](#dependencies))  

4. **Ensure SSH key for GitHub** (if using SSH) or Personal Access Token (if using HTTPS)

---

## Dependencies

This project relies on:

- **AWS CLI** – for interacting with AWS services  
- **Git** – version control and repository management  
- **Node.js / Python / other language dependencies** – depending on the app  
- **AWS SDK** – if your app interacts with AWS programmatically  
- **Docker** – optional, for containerized builds  

> Dependencies are managed via **AWS CodeArtifact** for secure versioning and consistent builds.

---

## Steps

1️⃣ **Set Up a Web App in the Cloud**  
I created the necessary AWS infrastructure to host my web application, including EC2 instances and networking configuration.

2️⃣ **Connect a GitHub Repo with AWS**  
Linked my GitHub repository to AWS, allowing automated integration and easy version tracking.

3️⃣ **Store Dependencies in CodeArtifact**  
Used **AWS CodeArtifact** to manage dependencies securely, ensuring consistent builds across environments.

4️⃣ **Package the App with CodeBuild**  
Configured **AWS CodeBuild** to compile, test, and package my application automatically.

5️⃣ **Deploy the App with CodeDeploy**  
Deployed the packaged application to AWS resources using **AWS CodeDeploy** for reliable updates.

⭐️ **Optional: Automate My Infrastructure with CloudFormation**  
Defined my infrastructure as code using **CloudFormation templates**, enabling repeatable and version-controlled deployments.

7️⃣ **CI/CD with CodePipeline**  
Set up automated pipelines with **AWS CodePipeline** to orchestrate building, testing, and deploying my application seamlessly.

---

## Conclusion

This project reflects my practical experience with AWS DevOps services, from setup and dependency management to automated CI/CD pipelines. It demonstrates how to take a web application from source code to fully deployed in the cloud, while using industry-standard DevOps practices.
