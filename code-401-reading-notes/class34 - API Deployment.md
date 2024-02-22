# Class 34 - API Deployment

## Reading

- [Django Settings Best Practices](https://djangostars.com/blog/configuring-django-settings-best-practices/)
    - Includes tips and best practices for Django projects
    - Include a separate settings_local.py file for dev builds and a normal settings.py for prod builds
    - Keep settings in environment variables
    - Don't hardcode sensitive info and avoid uploading to Git
    - Split settings into groups: Djagno, third-party, project

## Bookmark and Review

- [White Noise](http://whitenoise.evans.io/en/stable/)
    - Tutorial on WhiteNoise setup with Django proejcts
- [CORS](https://en.m.wikipedia.org/wiki/Cross-origin_resource_sharing)
    - Allows a balance of resource sharing with application security

## Reading Questions

### What are the key principles to follow when organizing and configuring Django settings for a project, according to the "Django Settings Best Practices" reading?

- Split dev build settings and prod build settings into different settings.py files
- Put sensitive information into environmental variables and avoid uploading to Git
- Split settings into different groups: Django, third-party, project

### How does the White Noise library contribute to the efficient serving of static files in a Django application, and what are the steps to integrate it into a project?

- The White Noise library fixes the styling for a Django Project using simplejwt library
- pip install whitenoise
- add whitenoise to settings.py middleware
- add STATIC_ROOT = BASE_DIR / "staticfiles"
- python manage.py collectstatic

### What is the purpose of Cross-Origin Resource Sharing (CORS) in web applications, and how can it be implemented and configured in a Django project to control access to resources?

- Allows a balance of resource sharing with application security
- pip install django-cors-headers
- Add 'corsheaders' to INSTALLED_APPS
- Add 'corsheaders.middleware.CorsMiddleware' to MIDDLEWARE
- Configure CORS policies, Allow Methods, and Headers

## Things I want to know more about

- Are Django environmental variables similar to React environmental variables which is the file that stores API keys?
