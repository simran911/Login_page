# Flask Authentication System

This project is a simple user authentication system built with Flask, SQLAlchemy, and Python. It allows users to register, log in, and log out. The system securely stores user data using SQLAlchemy ORM with a SQLite database.

## Features

![Screenshot 2024-09-06 194123](https://github.com/user-attachments/assets/9222e749-27e5-43a9-995f-6ebffff337e8)




- User Registration
![Screenshot 2024-09-06 194350](https://github.com/user-attachments/assets/0ed7d2bf-7df5-4bb1-b94e-de6f937f9d38)


- User Login
- ![Screenshot 2024-09-06 195837](https://github.com/user-attachments/assets/5b961388-4cec-42b1-8749-084a8980ef22)    
- User Logout
- ![Screenshot 2024-09-06 195856](https://github.com/user-attachments/assets/0c349c2f-d038-4f85-ae2d-22b1f15a5bf2)

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
