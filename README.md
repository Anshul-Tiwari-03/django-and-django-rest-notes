# Django and Django Rest Framework Project

This is a Django project that utilizes Django Rest Framework (DRF) to build RESTful APIs.

## Setup

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Anshul-Tiwari-03/django-and-django-rest-notes.git
    ```

2. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Run migrations:**

    ```bash
    python manage.py migrate
    ```

4. **Start the development server:**

    ```bash
    python manage.py runserver
    ```

    The server will be running at `http://localhost:8000/`.

## Project Structure

The project structure follows the standard Django project layout:

django-and-django-rest-notes/
│
├── myapp/ # Django app directory
│ ├── migrations/ # Database migrations
│ ├── templates/ # HTML templates (if applicable)
│ ├── init.py
│ ├── admin.py
│ ├── apps.py
│ ├── models.py # Django models
│ ├── tests.py # Unit tests
│ └── views.py # Django views
│
├── myproject/ # Django project directory
│ ├── init.py
│ ├── settings.py # Django settings
│ ├── urls.py # URL routing
│ └── wsgi.py # WSGI configuration for deployment
│
├── manage.py # Django management script
└── requirements.txt # List of project dependencies


## Dependencies

- Django
- Django Rest Framework

## Additional Information

- [Django Documentation](https://docs.djangoproject.com/en/stable/)
- [Django Rest Framework Documentation](https://www.django-rest-framework.org/)

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
