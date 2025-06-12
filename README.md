
# 🐳 Project: Dockerized Flask App with Jenkins CI/CD

## 🚀 Overview
This project demonstrates building and deploying a **Flask web application** using **Docker**, automated by **Jenkins pipelines** running on an **AWS EC2 instance**.

---

## 📦 Architecture Diagram

```
GitHub → Jenkins (on EC2) → Docker Build → Container → Port 5000
```

---

## 📁 Folder Structure

```
jenkins-docker-flask/
├── app/
│   └── app.py             # Flask app code
├── Dockerfile             # Docker build instructions
├── jenkins/
│   └── Jenkinsfile        # CI/CD pipeline definition
└── README.md              # Project documentation
```

---

## ⚙️ Tools Used

- **Flask** (Python Web Framework)
- **Docker** (Containerization)
- **Jenkins** (CI/CD Pipeline)
- **AWS EC2** (Hosting Jenkins)

---

## 🔄 CI/CD Flow

1. Developer pushes code to GitHub.
2. Jenkins is triggered and runs pipeline.
3. Pipeline stages:
   - Build Docker image
   - Run container on EC2

---

## ✅ How to Use

1. Setup Jenkins on EC2 (use prebuilt AMI or install manually)
2. Add pipeline job pointing to this repo
3. Use the `Jenkinsfile` to build & deploy

---

## 📈 What You Showcase to Recruiters

- Jenkins + Docker pipeline automation
- Flask app deployment using CI/CD
- Real AWS infrastructure and CI practice
