# Django Portfolio

A personal portfolio website built with Django.

## Project Structure

```
myportfolio/
├── base/                 # Main application
│   ├── templates/base/   # HTML templates
│   ├── admin.py          # Admin configuration
│   ├── models.py         # Database models
│   ├── views.py          # View functions
│   └── urls.py           # URL routing
├── myportfolio/          # Project settings
│   ├── settings.py       # Django settings
│   ├── urls.py           # Main URL configuration
│   └── wsgi.py           # WSGI configuration
├── static/               # Static files
│   ├── css/              # Stylesheets
│   └── images/           # Images
├── manage.py             # Django management script
└── db.sqlite3            # SQLite database
```

## Features

- Home page view
- Django admin interface
- Static file serving (CSS, images)
- Media file support

## Requirements

- Python 3.x
- Django 6.0.3

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd django-portfolio
   ```

2. Navigate to the project directory:
   ```bash
   cd myportfolio
   ```

3. (Optional) Create and activate a virtual environment:
   ```bash
   python -m venv venv
   # Windows
   venv\Scripts\activate
   # Linux/Mac
   source venv/bin/activate
   ```

4. Install dependencies:
   ```bash
   pip install django
   ```

5. Run migrations:
   ```bash
   python manage.py migrate
   ```

6. Create a superuser (optional, for admin access):
   ```bash
   python manage.py createsuperuser
   ```

## Running the Server

Start the development server:

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser.

## Admin Panel

Access the Django admin at `http://127.0.0.1:8000/admin/` (after creating a superuser).

## Development

- **Home page**: `base/views.py`
- **Templates**: `base/templates/base/`
- **Static files**: `static/css/`, `static/images/`
- **Models**: `base/models.py`

## License

This project is open source.
