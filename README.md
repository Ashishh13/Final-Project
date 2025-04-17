# Final Project: Flask + Django + Docker Compose

This project demonstrates a web application setup using both **Flask** and **Django**, containerized with **Docker Compose**. The Flask app serves as a lightweight microservice, while the Django app acts as the primary web backend with database support.

## 🔧 Project Structure

Final-Project/ ├── flask_app/ │ └── app.py ├── django_app/ │ ├── manage.py │ └── finalproject/ │ └── settings.py ├── docker-compose.yml ├── Dockerfile-flask ├── Dockerfile-django └── README.md


## 🚀 How to Run the Project

### Prerequisites

Make sure you have the following installed:

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

### Step-by-step Instructions

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/YourUsername/Final-Project.git
   cd Final-Project
Start the Services:

From the root directory, run:
docker-compose up --build

Access the Apps:
Flask app: http://localhost:5000
Django app: http://localhost:8000

To Stop the Services:
docker-compose down

What Each Component Does
Flask App: Simple API endpoint returning a greeting or sample data.
Django App: Main application with potential for admin panel, models, and REST API endpoints.
Docker Compose: Orchestrates both containers and links them via a common network.

Docker Images
You can also find the containerized versions of this app on Docker Hub:
Flask: https://github.com/Ashishh13/Final-Project/tree/main/flask_app
Django: https://github.com/Ashishh13/Final-Project/tree/main/django_app

Author
Ashish Signh_A4_67

