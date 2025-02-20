# Online Shop – Hackathon Phase 1 Submission

## Project Overview  
This project is an **Online Shop** built as part of the **Hackathon Phase 1 Submission**. It showcases proficiency in **Git & GitHub, Linux, and Docker**, covering repository management, system administration tasks, and containerization best practices.

## Tasks & Implementations  

### Git & GitHub
- Used **Git for version control**, effectively managing branches.  
- Maintained a **clean commit history** with meaningful commit messages.  
- Created **pull requests and merged changes** efficiently.

### Linux
- Set up an **Ubuntu EC2 instance** for deployment.  
- Used **Linux commands** for system administration.  
- Managed **file permissions, environment variables, and processes**.  

### Docker & Nginx
- Built a **Dockerfile** to containerize the application.  
- Created a **docker-compose.yml** file to manage multiple services (Nginx & MySQL).  
- Configured **Nginx as a reverse proxy** to serve the application.  

---

## How to Run the Application Locally  

### 1️⃣ Clone the Repository  
Open your terminal and run the following command:  

git clone <repo-link>
cd online_shop

### 2️⃣ Build and Start Services with Docker
Ensure Docker and Docker Compose are installed on your system.
Then, run the following command:

docker-compose up --build -d

✅ This will:
Build the application
Start Nginx (port 8080) & MySQL (port 3306)
Serve the app on:

http://localhost:8080

### 3️⃣ Verify Running Containers
To check if the containers are running, execute:

docker ps

### 4️⃣ Stopping the Application
To stop and remove the running containers, use:

docker-compose down

## 🔥 Key Changes & Enhancements
✅ Added Docker support with optimized Dockerfile & Docker Compose setup.

✅ Configured Nginx for production-ready deployment.

✅ Enhanced security by properly handling environment variables.

✅ Deployed to EC2

## 📢 Final Submission Statement
This repository represents my final submission for Hackathon Phase 1.

## 🏷️ Version/Branch Information
Final submission branch: feature/devops-feature

🎥 Video Demo
📹 Watch the demo here (3-5 minutes).

