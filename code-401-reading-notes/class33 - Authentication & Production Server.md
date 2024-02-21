# Class 33 - Authentication & Production Server

## Reading

- [JSON Web Tokens](https://jwt.io/introduction/)
    - JWT (JSON Web Token) Defines a way to securely transmit info as a JSON object and is commonly used for sharing data with authenticated users
    - It's digitally signed with a HMAC algorithm or a public/private key pair
    - JWTs can also be encrypted 
    - JWTs encoded structure: Header, Payload, Signature
    - JWTs need to be decoded prior to exchanging of information
- [DRF JWT Authentication](https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html)
    - Tutorial on how to integrate JWT into Django project
    - ```pip install djangorestframework_simplejwt```
    - Then update settings.py and urls.py with tutorial code
    - May need to refer back to previous readings tutorials to review authentication updates to views and models
- [Django Runserver Is Not Your Production Server](https://build.vsupalov.com/django-runserver-in-production/)
    - ```runserver``` command is for development only and does not include production necessary security audits or performance tests
    - For a production-ready Django project, use Nginx for the web server and Gunicorn for the application server
- [White Noise](https://whitenoise.readthedocs.io/en/stable/django.html)
    - Tutorial on WhiteNoise setup with Django proejcts
    
## Videos

- [Optional: JWT with DRF](https://www.youtube.com/watch?v=Fhcn2qx-4VQ)

## Bookmark and Review

- [Gunicorn](https://gunicorn.org/)
- [Django Migrations Primer](https://realpython.com/django-migrations-a-primer/)

## Reading Questions

### What is the primary purpose of JSON Web Tokens (JWTs) and how do they work in terms of encoding and decoding data?

- JWTs help securely share information to authenticated users. An encoded JWT follows the structure header, payload, signature and needs to be decoded to verify authentication of the user prior to the exchanging of data from server to user

### How does JWT Authentication integrate with Django REST Framework to secure API endpoints, and what are the key components involved in this process?

- Install simplejwt package, update settings.py with jwt info, update views, urls and models to handle user authentication process, then each time a user makes an API request, it will go through the JWT authentication process

### Why is Django's built-in runserver not suitable for production environments, and what are some alternative server options that should be considered for deploying a Django application?

- Django development servers do not include necessary security audits and performance tests necessary for production servers
- Alternatives are Nginx for web servers and Gunicorn for WGSI application servers

## Things I want to know more about

- How do you setup Nginx and Gunicorn with a production-ready Django project?
