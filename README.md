# Docker Portfolio Website 🐳

This is a beginner-friendly Docker project where I containerized a simple static portfolio website using Docker and Nginx.

The purpose of this project is to understand Docker basics such as Dockerfile, images, containers, and port mapping through hands-on practice.

---

## 🚀 Project Description

In this project:
- A static portfolio website is created using HTML and CSS
- Nginx is used as a web server
- A Dockerfile is written to containerize the website
- The website runs inside a Docker container using port mapping

This project runs locally using Docker Desktop and does not use any cloud services, so there is no cost involved.

---

## 🛠 Technologies Used

- Docker
- Nginx
- HTML
- CSS
- Git
- GitHub

---

## 📂 Project Structure

docker-portfolio/
├── index.html
├── style.css
└── Dockerfile


---

## 🐳 Dockerfile Overview

- **FROM nginx:latest**  
  Uses the official Nginx image

- **COPY . /usr/share/nginx/html**  
  Copies website files into the container

- **EXPOSE 80**  
  Exposes port 80 inside the container

---

## ▶️ How to Run This Project

### 1️⃣ Clone the repository
```bash
git clone https://github.com/chetanambalkar329-dot/docker-portfolio.git
cd docker-portfolio
docker build -t docker-portfolio .
docker run -d -p 8080:80 docker-portfolio
http://localhost:8080

📸 Screenshot
![Docker Portfolio Running](<img width="1904" height="989" alt="screenshot" src="https://github.com/user-attachments/assets/d5ff7e7d-9acb-4b3b-8389-80fdaca2f2d4" />
)
