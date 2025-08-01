# 🧠 Chatbot API - Django REST Framework

This project is a simple chatbot API built using Django and Django REST Framework. It allows users to send messages to a chatbot and receive automated responses.

## 🚀 Features

- RESTful endpoints to interact with the chatbot
- Token Authentication for API security
- Rule-based logic for chatbot responses
- Easy to extend with AI/ML models or third-party APIs

## 📦 Requirements

- Python 3.8+
- Django 4.x
- djangorestframework
- (Optional) PostgreSQL or Docker

## ⚙️ Setup Instructions

```bash
# Clone the repo
git clone https://github.com/yourusername/chatbot_api.git
cd chatbot_api

# Set up virtual environment
python -m venv env
source env/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start server
python manage.py runserver
