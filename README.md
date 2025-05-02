Django Tutorial - Amirkabir University
Overview
This repository contains the materials and code for the Django tutorial taught by Mohammad Mahdi Hassani at Amirkabir University of Technology. The tutorial is designed to introduce students to web development using the Django framework, a high-level Python web framework that encourages rapid development and clean, pragmatic design.
Prerequisites
Before starting this tutorial, ensure you have the following installed:

Python 3.8 or higher
pip (Python package manager)
Virtualenv (recommended for managing dependencies)
Git (for cloning this repository)

Getting Started
Follow these steps to set up the project locally:

Clone the Repository
git clone https://github.com/MohammadMahdiHassani/Django_Toturial.git
cd Django_Toturial


Create and Activate a Virtual Environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


Install Dependencies
pip install -r requirements.txt


Apply Migrations
python manage.py migrate


Run the Development Server
python manage.py runserver

Open your browser and navigate to http://127.0.0.1:8000/ to view the application.


Tutorial Structure
The tutorial is divided into the following sections:

Introduction to Django
Setting up a Django project
Understanding Django's MVT architecture


Models and Databases
Defining models
Performing migrations
Using the Django Admin interface


Views and Templates
Creating views (function-based and class-based)
Rendering templates
Passing data to templates


Forms and User Input
Handling forms
Validating user input


User Authentication
Implementing login/logout functionality
Managing user permissions


Deployment
Preparing the project for production
Deploying to a hosting platform (e.g., PythonAnywhere)



Project Structure
django-tutorial-amirkabir/
├── myproject/              # Main Django project directory
│   ├── __init__.py
│   ├── settings.py         # Project settings
│   ├── urls.py             # URL routing
│   └── wsgi.py             # WSGI configuration
├── myapp/                  # Sample application
│   ├── migrations/         # Database migrations
│   ├── templates/          # HTML templates
│   ├── __init__.py
│   ├── admin.py            # Admin panel configuration
│   ├── models.py           # Database models
│   ├── tests.py            # Unit tests
│   ├── urls.py             # App-specific URLs
│   └── views.py            # View functions/classes
├── manage.py               # Django management script
├── requirements.txt        # Project dependencies
└── README.md               # This file

Contributing
This repository is primarily for educational purposes. If you find any issues or have suggestions for improvement, please:

Open an issue in the GitHub repository.
Submit a pull request with your proposed changes.

Contact
For questions or further information, contact Mohammad Mahdi Hassani via the Amirkabir University email or reach out through the course platform.
Acknowledgments

Django Documentation (https://docs.djangoproject.com/)
Amirkabir University of Technology
The Django community for their extensive resources and support

