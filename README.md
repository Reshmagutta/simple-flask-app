# 🌍 Travel App – DevOps Lab Project

A **Flask-based Travel Application** that showcases popular destinations and travel information. This project applies core **DevOps principles**, including **containerization using Docker**, **version control with Git**, and **CI/CD automation using GitHub Actions**.

---

## 📄 Documentation

All detailed documentation is provided in the `documentation.pdf` file inside this repository. It includes requirements, architecture, setup, and DevOps implementation steps.

---

## 📁 Project Structure

.
├── app.py # Main Flask application
├── requirements.txt # Python dependencies
├── Dockerfile # Docker containerization file
├── documentation.pdf # Project documentation
├── static/ # Static files (CSS, images)
│ └── style.css # Stylesheet
└── templates/ # HTML templates
└── index.html # Travel homepage UI

---

## ✨ Features

- 🌆 Beautifully designed travel destinations (e.g., Paris, Tokyo)
- 📱 Responsive UI using HTML/CSS
- 🐳 Dockerized Flask app for consistent environment setup
- 🔁 CI/CD-ready project structure
- 👩‍🎓 Footer credits with author name (**Reshma Gutta**)

---

## 🛠️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Reshmagutta/travel-app-flask.git
cd travel-app-flask
2️⃣ Build and Run with Docker
docker build -t travel-app .
docker run -p 5000:5000 -d --name travel-app-container travel-app
Open your browser at 👉 http://localhost:5000

