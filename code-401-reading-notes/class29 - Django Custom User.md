# Class 29 - Django Custom User

## Reading

- [Django Custom User Model](https://learndjango.com/tutorials/django-custom-user-model)
    - Django offers built-in User model for authentication
    - However, docs recommend to use a custom user model because it provides more flexibility
- [DjangoX](https://github.com/wsvincent/djangox)
    - DjangoX is a project template that enables developers to quickly startup a new Django project
    - Includes custom user model, authentication and permissions, Docker-ready

## Videos

### [Choose one:]

- [Creating a Custom User Model](https://www.youtube.com/watch?v=eCeRC7E8Z7Y&t=59s)
- [Abstract User, User Profile and Signals in Django](https://www.youtube.com/watch?v=EudKs1HPUfE)
    - Tutorial that demonstrates how to add extra fields for a User Model in a new project or a project in development
    - Includes example codeblocks for class User Model

## Bookmark and Review

- [Substituting a custom User model](https://docs.djangoproject.com/en/3.0/topics/auth/customizing/#auth-custom-user)

## Reading Questions

### What are the key benefits of using a Django Custom User Model, and how does it differ from the default Django User Model?

- Default Django User Model is built-in however Django docs recommend to use a Custom User Model for all new Django projects
- Custom User Model provides more flexibility and allows apps to require additional or more requirements for user generation and could potentially make the app more secure

### Explain the process of creating and implementing a Custom User Model in Django, including the necessary changes to settings.py and the required model fields.

- Create a new app using the command ```python manage.py startapp accounts```
- In settings.py, modify INSTALLED_APPS to include ```accounts``` and the AUTH_USER_MODEL config to say```"accounts.CustomUser"```
- In models.py import ```AbstractUser``` ```from django.contrib.auth.models``` and create the model class
- Create a new file called forms.py and import ```UserCreationForm, UserChangeForm``` ```from django.contrib.auth.forms``` and create the form classes
- In admin.py, register the User Models
- In GitBash, makemigrations and migrate accounts

### What is DjangoX and how does it complement or extend the functionality of Django? Provide an example use case for incorporating DjangoX in a project.

- DjangoX is a project template that enables developers to quickly startup a new Django project
- Includes custom user model, authentication and permissions, Docker-ready
- Building a mock-Spotify web app. Spotify was built using Django and if someone is interested in recreating that app, then DjangoX can help speed up that development process because it includes a lot of built-in features that Spotify probably uses

## Things I want to know more about

- Why wouldn't I use DjangoX to start my next project? Is there any negatives to using this pre-configured setup?
