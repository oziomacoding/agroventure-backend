# Agriculture site's contact form  validation

An application built with Django RESTful APIs.
## Table of Contents
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the Application](#running-the-application)

## Technologies Used
- **Backend**: Django, Django REST Framework
- **Database**: SQLite

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/oziomacoding/agroventure-backend.git
   cd agroventure-backend
2. Set up a virtual environment:
   python -m venv env
  source env/bin/activate  # On Windows use `env\Scripts\activate`
3. Install dependencies:
   pip install -r requirements.txt

## Configuration

### Generate a Secret Key
To run the application, you need to generate a unique `SECRET_KEY`. Here is a way to do that:

1. **Using Django's Utility**:
   If you have Django installed, run the following command in your terminal:
   ```bash
   python -c 'from django.core.management.utils import get_random_secret_key; print(get_random_secret_key())'

   This command will output a randomly generated secret key that you can use.
2. Create a .env file in the root directory and add the following variables:
   SECRET_KEY='your-generated-secret-key'  # Replace with your actual secret key
   DEBUG=True
   ALLOWED_HOSTS=localhost

## Running the Application

1. Create a .env file in the root directory and add the following variables:
2. Run migrations:
   python manage.py migrate
3. Start the Django server:
   python manage.py runserver


