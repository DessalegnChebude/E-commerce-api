# E-commerce Product Management API

## Setup Instructions

1. Clone the repository:
   - git clone <repository_url>

2. Navigate into the project directory:
    - cd ecommerce_api
3. Create a virtual environment
    - python -m venv e-commerce
4. Activate the virtual environment
    - venv\Scripts\activate for - windows
    - source venv/bin/activate  - on macOS
5. Install the required packages
    - pip install django djangorestframework
6. Create a new django project
    - django-admin startproject ecommerce_api
7. Create a new django app called product
    - python manage.py createapp product
6. Run migrations
    - python manage.py migrate
7. Start the development server
    - python manage.py runserver