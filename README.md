# Django Blog

A simple blog application built with Django. It features a list of all posts and individual posts, which can be managed through the built-in admin.

This project is the companion code for the [Django Blog Tutorial](https://learndjango.com/tutorials/django-blog-tutorial) on LearnDjango.com.

![Demo](django_blog_demo_1080.gif)

## Requirements
Python 3.14 & Django 6.0

## Installation

```bash
# Clone the repository
git clone https://github.com/wsvincent/django-blog.git
cd django-blog

# Create and activate a virtual environment:
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install dependencies:
python -m pip install django

# Run the database migrations:
python manage.py migrate
 
# Create a superuser to access the admin:
python manage.py createsuperuser

# Start the development server:
python manage.py runserver
```

The site will be available at http://127.0.0.1:8000. Add posts via the admin at http://127.0.0.1:8000/admin.
