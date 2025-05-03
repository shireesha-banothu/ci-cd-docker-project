# 🚀 CI/CD Pipeline with GitHub Actions & Docker (No Cloud Needed)

This project demonstrates a complete CI/CD pipeline setup using **Docker** and **GitHub Actions** for a simple Node.js application — fully containerized and deployed locally. No cloud services are required.

---

## 📁 Project Structure

ci-cd-docker-project/
├── .github/
│ └── workflows/
│ └── docker.yml
├── Dockerfile
├── index.js
├── package.json
└── README.md


---

## 🛠️ Tech Stack

- **Node.js** – Backend app
- **Docker** – Containerization
- **GitHub Actions** – CI/CD automation
- **DockerHub** – Hosting the built image

---

## ✅ Features

- Automatically builds and pushes Docker images to DockerHub
- Triggered on push to the `main` branch
- Simple Node.js app used for testing
- 100% local testing and deployment

---

## 🚧 Prerequisites

- Docker installed locally
- GitHub account
- DockerHub account
- GitHub Secrets for DockerHub credentials

---

## ⚙️ Setup & Installation

### 1. Clone the Repository

```bash
git clone https://github.com/shireesha-banothu/ci-cd-docker-project.git
cd ci-cd-docker-project

GitHub Secrets Setup
Go to: Repo → Settings → Secrets → Actions
Create the following secrets:

Secret Name	Description
DOCKER_USERNAME	Your DockerHub username
DOCKER_PASSWORD	Your DockerHub password or token

 DockerHub Image
View image here:
➡️ https://hub.docker.com/r/siri1419/ci-cd-docker-project
Author
Shireesha Banothu
GitHub: @shireesha-banothu
DockerHub: siri1419

