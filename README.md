# emart-app

**Emart App** is a modern e-commerce platform that combines a dynamic Node.js backend, Java APIs, and a frontend served via NGINX, all containerized using Docker. It supports product browsing, user authentication, admin controls, and more, with data stored in MongoDB and MySQL.

---
# If you are using Vagrant, I had attached the vagrant file in the repository clone it and follow the steps. 

## 🚀 Tech Stack

| Layer         | Technology             |
|---------------|------------------------|
| Frontend      | Angular (served via Node.js build) |
| Backend API   | Node.js (Express)      |
| Java API      | Java (Spring Boot or REST API) |
| API Gateway   | NGINX                  |
| Databases     | MongoDB & MySQL       |
| Containerization | Docker, Docker Compose |

---

## 📁 Project Structure

emart-app/
│
├── client/ # Angular frontend app
├── nodeapi/ # Node.js backend (API service)
├── javaapi/ # Java API service
├── nginx/ # NGINX config
├── docker-compose.yaml
├── Dockerfile # Multi-stage Docker build
└── README.md

## 🧪 How to Run the Application

### 🐳 Step 1: Clone the repository

```bash
git clone https://github.com/ashutoshojha18/emartapp-docker.git
cd emart-app
docker-compose build
docker-compose up -d
bash ``` 

# Now check on port 80
