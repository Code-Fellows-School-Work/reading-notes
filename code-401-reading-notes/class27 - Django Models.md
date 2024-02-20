# Class 27 - Django Models

## Reading

- [Using Models](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models)
    - Django web apps access and manage data through Python objects called Models
    - Models define the structure of stored data, including field types, maximum size, default values, etc.
    - Once the Model is defined, Django will do all the under-the-hood work to communicate with the database
- [Django Admin](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site)
    - Admin app for a Django website that interfaces with Django Models to create, view, update and delete records
    - Help speed up deployment process by having a already made CRUD app that can be used to test and verify working Models
    - Need to update admin.py to connect Models to Admin

## Bookmark and Review

- [(Optional): Beginner's Guide to Django - Part 1](https://simpleisbetterthancomplex.com/series/2017/09/04/a-complete-beginners-guide-to-django-part-1.html)
- [Beginner's Guide to Django - Part 2](https://simpleisbetterthancomplex.com/series/2017/09/11/a-complete-beginners-guide-to-django-part-2.html)

## Reading Questions

### Explain the purpose and basic structure of Django models. How do they help in creating and managing database schema in a Django application?

- Django Models help web applications interact with databases without using convential databases query methods. 
- Basic structure of a Django model is a class with attributes connected to information contained within a database

### Describe the primary features and functionality of the Django Admin interface. How can it be customized to suit the specific needs of a project?

- Includes authentication system with a customizable display. Includes form customization to create and edit Model instances aligned with project requirements.

### Briefly outline the key components and workflow of a Django application, as discussed in the Beginner's Guide to Django. How do these components interact with each other to create a functional web application?

Reused from my retro, steps to start a Django application:
- When starting django app, remember the . at the end
    - for example - django-admin start project django_snacks_project .
- Creating an app:
    - python manage.py startapp snacks (plural naming-convention)
- Add gitignore, readme, and initalize git repo
- In the app folder, add class to views.py
- In the app folder, add urls.py
- In projects.urls add ```path('', include('snacks.urls')),```
- Create templates folder with html file
- In settings.py add ```BASE_DIR/'templates',``` to 'DIRS'
- In base.html, add ```{% block content %} and {% endblock content %}```

## Things I want to know more about

- Can you explicitly assign what sort of database a Django app will interface with or is there a default? Either SQL, NoSQL, MySQL, etc?
