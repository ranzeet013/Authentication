# Authentication Application

This is a FastAPI-based web application with user authentication features. It leverages SQLAlchemy for database management, Jinja2 for templating, and serves static files.

## Features

- **User authentication (login and registration):** Users can create accounts and log in securely.
- **Password hashing using `passlib`:** Ensures secure storage of passwords by hashing them.
- **Database integration with SQLAlchemy:** Manages data persistence using an ORM (Object-Relational Mapper).
- **Templating with Jinja2:** Renders HTML templates dynamically with Python variables.


## Requirements

To run the application, ensure the following are installed:
- **Python 3.10 or higher:** The base programming language used for the project.
- **FastAPI:** The web framework for building APIs.
- **SQLAlchemy:** A database toolkit and ORM for Python.
- **Jinja2:** A templating engine for rendering HTML.
- **Uvicorn:** An ASGI server to run the application.
- **passlib:** A library for hashing and verifying passwords.

## Installation

1. **Clone the repository:** Download the project files from the repository.
   ```bash
   git clone <repository_url>
   cd <repository_name>

2. **Set Up a Virtual Environment:** Create a virtual environment to isolate the dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activat

3. **Install Dependencies:** Use pip to install the required Python packages:
   ```bash
   pip install -r requirements.txt

## Run the Application

1. **Start the Server:** Run the application using Uvicorn:
   ```bash
   uvicorn main:app --reload
- The --reload flag enables auto-reloading during development.

2. **Access the Application:** Open your browser and navigate to:  http://127.0.0.1:8000

- This will display the homepage or API documentation.

## Conclusion :

By following the steps above, you’ve successfully installed and run the FastAPI Authentication application. This setup provides a foundation for exploring the application's features, such as user authentication, static file serving, and integration with SQLAlchemy.
