Travel App – DevOps Lab Project
A Flask-based Travel Application that showcases popular destinations and travel information. This project applies core DevOps principles, including containerization using Docker, version control with Git, and CI/CD automation using GitHub Actions.

 Documentation
All detailed documentation is provided in the documentation.pdf file inside this repository. It includes requirements, architecture, setup, and DevOps implementation steps.

📁 Project Structure
csharp
Copy
Edit
.
├── app.py              # Main Flask application
├── requirements.txt    # Python dependencies
├── Dockerfile          # Docker containerization file
├── documentation.pdf   # Project documentation
├── static/             # Static files (CSS, images)
│   └── style.css       # Stylesheet
└── templates/          # HTML templates
    └── index.html      # Travel homepage UI
✨ Features
Beautifully designed travel destinations (e.g., Paris, Tokyo)

Responsive UI using HTML/CSS

Dockerized Flask app for consistent environment setup

CI/CD-ready project structure

Footer credits with author name (Reshma Gutta)

🛠️ Setup Instructions
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/Reshmagutta/travel-app-flask.git
cd travel-app-flask
2️⃣ Build and Run with Docker
Build Docker Image:

bash
Copy
Edit
docker build -t travel-app .
Run the Docker Container:

bash
Copy
Edit
docker run -p 5000:5000 -d --name travel-app-container travel-app
Now visit the app in your browser:
👉 http://localhost:5000

📤 (Optional) Push to Docker Hub
Tag the Docker image:

bash
Copy
Edit
docker tag travel-app yourusername/travel-app:latest
Push the image:

bash
Copy
Edit
docker login
docker push yourusername/travel-app:latest
🧪 Local Development (Without Docker)
Set up Python environment:

bash
Copy
Edit
python -m venv venv
.\venv\Scripts\activate  # For Windows
source venv/bin/activate  # For macOS/Linux
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the app:

bash
Copy
Edit
python app.py
Then open http://localhost:5000 in your browser.

DevOps Best Practices Implemented
✅ Containerization using Docker

✅ CI/CD-ready structure (can integrate GitHub Actions)

✅ Environment isolation via Docker & virtualenv

✅ Clean project structure for scalability

✅ Documentation-first approach

👩‍💻 Author
Built with ❤️ by Reshma Gutta
