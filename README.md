# GIAIC Docker Homework – FastAPI Agents SDK

This repository contains my Docker homework for **GIAIC**, where I successfully dockerized a FastAPI project and ran it inside a Docker container.

The goal of this assignment was to understand Docker basics, build a Docker image using a Dockerfile, run a container, and verify the application using a browser and Swagger UI.

---

## 🚀 Project Overview

- FastAPI-based backend project  
- Dockerized using a custom Dockerfile  
- Docker image built successfully  
- Container run locally using Docker  
- APIs tested via browser and Swagger UI  

---

## 🛠 Tech Stack

- **Python** 3.12  
- **FastAPI**  
- **Uvicorn**  
- **Docker**

---

## 📁 Project Structure

giaic-docker-homework/
│
├── fastapi-agents-sdk/
│ ├── Dockerfile
│ ├── main.py
│ ├── connection.py
│ ├── tools.py
│ ├── requirements.txt
│ ├── pyproject.toml
│ └── README.md
│
└── README.md



---

## 🐳 How to Run the Project Using Docker

### 1️⃣ Build Docker Image

Run the following command in the project directory:

```bash
docker build -t fastapi-homework .

2️⃣ Run Docker Container

docker run -p 8000:8000 fastapi-homework

3️⃣ Open Application in Browser
Application URL:
http://localhost:8000

Swagger API Docs:
http://localhost:8000/docs

✅ Output Verification
Docker image builds successfully

Container runs without errors

FastAPI application responds correctly

Swagger UI loads and APIs are accessible

Image visible in Docker Desktop under Images section

📚 What I Learned
Difference between Docker images and containers

Writing and understanding a Dockerfile

Docker build and run commands

Port mapping in Docker

Debugging Docker and dependency issues

Handling nested Git repository issues

🔐 Security Notes
No API keys or secrets are included in this repository

.env files are not committed

Project is safe to be shared publicly

🙌 Acknowledgment
Thanks to GIAIC instructors for providing hands-on Docker learning and practical assignments that helped build real-world skills.

👤 Author
Moheeb
GIAIC Student

📌 Status
✅ Homework completed
✅ Docker image built and tested
✅ Project successfully containerized



---

## ✅ Ab Final Commands Chalao

```bash
git add README.md
git commit -m "Add README for Docker homework"
git push
