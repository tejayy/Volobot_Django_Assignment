Volobot Django Assignment

This repository contains the Django project for the Volobot Django Assignment. The project is designed to manage sections and students, providing CRUD (Create, Read, Update, Delete) functionality through Django REST Framework.
Project Structure

The project is organized as follows:

    myapp: Django app containing models, serializers, views, forms, and templates.
        models.py: Defines the Section and Student models.
        serializers.py: Contains serializers for Section and Student models.
        views.py: Implements views for CRUD operations and a home page.
        forms.py: Defines forms for creating sections and students.
        templates: Folder containing HTML templates for rendering the home page and forms.

    myproject: Django project settings.
        urls.py: Configures URL patterns for the project.

    manage.py: Django management script.

Getting Started
Prerequisites

    Python 3.x
    Django
    Django REST Framework

Installation

    Clone the repository:

    bash

git clone https://github.com/tejayy/Volobot_Django_Assignment.git

Navigate to the project directory:

bash

cd Volobot_Django_Assignment

Install dependencies:

bash

pip install -r requirements.txt

Apply migrations:

bash

python manage.py migrate

Create a superuser (optional):

bash

python manage.py createsuperuser

Follow the prompts to set up a superuser account to access the Django admin panel.

Run the development server:

bash

    python manage.py runserver

    The project will be accessible at http://127.0.0.1:8000/.

Usage
API Endpoints

    List all sections: http://127.0.0.1:8000/api/sections/
    Create a section: http://127.0.0.1:8000/api/sections/
    View, update, and delete a section: http://127.0.0.1:8000/api/sections/<section_id>/
    List all students within a section: http://127.0.0.1:8000/api/students/
    Create a student within a section: http://127.0.0.1:8000/api/students/
    View, update, and delete a student: http://127.0.0.1:8000/api/students/<student_id>/

Home Page

    Access the home page: http://127.0.0.1:8000/
        View, create, update, and delete sections and students.

Contributing

    Fork the repository.
    Create a new branch: git checkout -b feature/my-feature.
    Commit your changes: git commit -am 'Add new feature'.
    Push to the branch: git push origin feature/my-feature.
    Submit a pull request.

License

This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments

    Thanks to Volobot for the assignment.
