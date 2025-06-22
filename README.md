# Travel App Flask 🌍✈️

This is a simple Travel Web App built with Flask  
Created by **Reshma Gutta**

# Documentation

Detailed project documentation is available in the `documentation.pdf` file in this repository.  
It covers:
- Project requirements  
- System architecture  
- Implementation details  
- DevOps practices (Docker, CI/CD, etc.)

## 📁 Project Structure

.
├── app.py # Main Flask application with weather API integration
├── requirements.txt # Python dependencies
├── Dockerfile # Docker containerization file
├── documentation.pdf # Detailed project documentation
├── static/ # Static assets
│ └── style.css # CSS styling for the travel app
└── templates/ # HTML templates
└── index.html # App UI with search functionality

## How to Run

```bash
docker build -t travel-app-flask .
docker run -p 5000:5000 travel-app-flask
