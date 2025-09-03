**Task Smash**

Task Smash is a Flask-based task manager that lets users add, edit, and delete tasks. Built with Flask, SQLAlchemy, SQLite, and styled with SCSS, it’s fully containerized with Docker for easy deployment. Perfect for learning Flask fundamentals, database handling, and front-end integration.

**Features**

Add, edit, and delete tasks
View tasks in a structured table
Modern UI styled with SCSS
Dockerized for easy setup and deployment


**Tech Stack**

Backend: Python, Flask
Database: SQLite (SQLAlchemy ORM)
Frontend: SCSS
Containerization: Docker

**Installation & Run Locally**

# Clone the repository
git clone https://github.com/lavanyagopasana/Flask-Task-Manager-App.git
cd Flask-Task-Manager-App

# Build Docker image
docker build -t flask-task-manager .

# Run Docker container
docker run -p 5000:5000 flask-task-manager
Open your browser at http://localhost:5000 to access the app.

**Deployment**

Since the app is Dockerized, it can be deployed anywhere Docker is supported. Build and run the image as shown above.
