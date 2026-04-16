# Django Blog

A simple blog application built with Django. It features a list of all posts and individual posts, which can be managed through the built-in admin.

This project is the companion code for the [Django Blog Tutorial](https://learndjango.com/tutorials/django-blog-tutorial) on LearnDjango.com.

## Requirements

- Python 3.14 
- Django 6.0

## Installation

1. Clone the repository:

```bash
git clone https://github.com/wsvincent/django-blog.git
cd django-blog
```

2. Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install django
```

4. Run the database migrations:

```bash
python manage.py migrate
```

5. Create a superuser to access the admin:

```bash
python manage.py createsuperuser
```

6. Start the development server:

```bash
python manage.py runserver
```

The site will be available at http://127.0.0.1:8000. Add posts via the admin at http://127.0.0.1:8000/admin.
