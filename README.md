# 🚀 Cross-Account Docker Deployment with Amazon ECR

This project demonstrates how to build and deploy a Docker container using Amazon Elastic Container Registry (ECR), with cross-account access configuration. It's part of a collaborative learning challenge powered by **NextWork**.

## 📦 What I Did

### 🔨 Built a Custom Docker Image
- Created a `Dockerfile` using `nginx:latest` as the base image.
- Added a custom `index.html` to serve content via Nginx.

### ☁️ Pushed the Image to Amazon ECR
- Configured AWS CLI with IAM credentials.
- Authenticated Docker with ECR.
- Tagged and pushed the image to my private ECR repository.

### 🔒 Configured IAM for Cross-Account Access
- Created a new IAM user with `AmazonEC2ContainerRegistryReadOnly` permission.
- Shared access to my ECR repo with a teammate (Player B) by updating repository permissions.
- Allowed them to pull my Docker image securely.

### 💻 Pulled and Ran a Teammate’s Image Locally
- Pulled Player B’s image from their ECR.
- Ran the image on my local machine to test cross-account deployments.

## 🧠 Key Learnings
- Working with private ECR repositories
- Secure IAM access setup across AWS accounts
- Handling architecture compatibility between AMD64 and ARM64 systems

## 🕒 Time Spent
~3-4 hours including:
- Setting up ECR and IAM
- Troubleshooting permissions
- Resolving architecture compatibility issues

## 🌐 Resources Used
- [Docker](https://www.docker.com/)
- [AWS CLI](https://aws.amazon.com/cli/)
- [Amazon ECR](https://docs.aws.amazon.com/AmazonECR/latest/userguide/what-is-ecr.html)
- [NextWork Project](https://community.nextwork.org)

## 🤝 Project Partner
Worked with a peer as part of a multiplayer project on **NextWork** to simulate a real-world DevOps workflow.

---

### 🚀 Ready to Collaborate or Learn More?

Feel free to clone this project, give feedback, or connect with me!  
📧 dimashamadhushani413@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/dimasha-madhushani)

