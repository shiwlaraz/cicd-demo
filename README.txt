#  CI/CD Pipeline Flask App

A simple Flask web application deployed using a **CI/CD pipeline with GitHub and Render**. This project demonstrates a complete DevOps workflow from code development to cloud deployment.

---
##  Live 

 https://cicd-demo-jjw0.onrender.com
---

#  Project Overview

This project is a basic Flask web application designed to demonstrate:

- Web app development using Flask
- Git-based version control (GitHub)
- Cloud deployment (Render)
- Continuous Deployment (CI/CD pipeline)

Every change pushed to GitHub automatically triggers a new deploymenn Render.

---

#  Architecture

Developer → GitHub Repository → Render CID → Live Web App

---

#  Tech Stack

- Python 3
- Flask
- Gunicorn
- Git & GitH
- Render (Cloud Hosting)

---

#  Project Structure

cicd-demo/
│
├── app.py               # Flask application
├── requirements.txt     # Dependencies
├── Dockerfile           # Container setup (optional use)
└── READMmd            # Project documentation

---

# Features

- Simple Flask web server
- Health check endpoint (/health)
- CI/CD pipeline using GitHub + Render
- Auto deployme on every push
- Cud-hosted live application

---

#  API Endpoints

## me

GET /

Response:
CI/CD pipeline is working fine!

---

## Health Check

GET /health

Response:
OK

---

#  How to Run Locally

## 1. Clone the repository

git clone https://github.com/shiwlaraz/cicd-demo.git
cd cicd-demo

## 2. Install dependencies

pip install -r requirements.t

## 3. Run the app

python app.py

## 4. Open in browser

http://127.0.0.1:8080

---

# CI/CD Workflow

1. Developer pushes code to GitHub
2. Render detects new commit
3. Build proce installs dependencies
4. Application is deployed automatically
5. Live app is updated instantly

---

#  What I Learned

- Building and deploying a Flask app
- Using Git for version control
- nnecting GitHub with cloud deployment
- Understanding CI/CD pipeline concepts
- Real-world DevOps workflow

---

# Future Improvements

- Add database integration (PostgreSQL)
d user authentication
- Add Doker-based deployment
- Add GitHub Actions CI pipeline
- Add unit testing (pytest)

---

# Author

Shiwlaraz Das

---

# If you like this project

Star the repository 
