# Secure Web App (Flask)

A secure authentication-based web application built using Flask.

## Features
- User Registration & Login
- Password hashing using Bcrypt
- Session-based authentication
- SQLite database
- Secure Flask structure

## Tech Stack
- Python
- Flask
- Flask-Bcrypt
- SQLite
- HTML (Jinja Templates)

## Project Structure
secure-web-app/
├── app.py
├── database.db
├── templates/
│   ├── login.html
│   ├── register.html
│   └── dashboard.html
├── .gitignore
└── README.md

## How to Run
```bash
pip install flask flask-bcrypt
python app.py
