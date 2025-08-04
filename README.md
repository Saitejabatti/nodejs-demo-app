\# Node.js Demo App – CI/CD Pipeline 🚀

This is a simple Node.js web app built with Express, Dockerized, and deployed using a GitHub Actions CI/CD pipeline.

\## 👨‍💻 Developer

\*\*Batti Sai Teja\*\* – DevOps Intern at Elevete Labs

\## 🔧 Tech Stack

\- Node.js

\- Express

\- Docker

\- GitHub Actions

\- DockerHub

\## 🛠️ Features

\- Runs a basic web server on port 3000

\- Dockerized for easy container deployment

\- Automated CI/CD pipeline:

&nbsp; - Test

&nbsp; - Build Docker Image

&nbsp; - Push to DockerHub

\## 🔁 CI/CD Pipeline Flow

push to main → GitHub actions → test → build → Docker image → push to DockerHub

📦 DockerHub Image
https://hub.docker.com/repository/docker/saitejabatti/nodejs-demo-app

🚀 Run Locally (without Docker)

git clone https://github.com/Saitejabatti/nodejs-demo-app.git

cd nodejs-demo-app

npm install

npm start

🐳 Run with Docker
docker pull YOUR\_USERNAME/nodejs-demo-app

docker run -p 3000:3000 YOUR\_USERNAME/nodejs-demo-app

✅ Output

Visit http://localhost:3000 to see:

🚀 Hello from Node.js Demo App!










