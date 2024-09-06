# Flask Authentication System

This project is a simple user authentication system built with Flask, SQLAlchemy, and Python. It allows users to register, log in, and log out. The system securely stores user data using SQLAlchemy ORM with a SQLite database.

## Features

![Screenshot 2024-09-06 194123](https://github.com/user-attachments/assets/9222e749-27e5-43a9-995f-6ebffff337e8)




- User Registration
- User Login
- User Logout
- Password Hashing for Security
- User Session Management

## Technologies Used

- Python
- Flask
- SQLAlchemy
- SQLite
- HTML/CSS (for templates)

## Setup and Installation

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/your-repo-name.git


### Install dependencies:
pip install flask sqlalchemy flask_sqlalchemy


### Set up the SQLite database:

>>> from yourapp import db
>>> db.create_all()

### Run the Flask application:
python app.py


### Project Structure

.
├── app.py                # Main Flask application
├── models.py             # SQLAlchemy models
├── templates/
│   ├── register.html     # User registration page
│   ├── login.html        # User login page
│   └── home.html         # Home page
└── static/
    └── styles.css        # Styling for templates
