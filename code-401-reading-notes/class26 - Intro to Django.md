# Class 26 - Intro to Django

## Reading

- [Getting started with Django](https://www.djangoproject.com/start/)
    - Installation, documentation and example beginner apps for Django
    - High-level Python web framework that enables rapid development of secure and maintainable websites
    - Takes care of under-the-hood requirements so devs can focus on app development
- [How Django Works Behind the Scenes](https://wsvincent.com/how-django-works-behind-the-scenes/)
    - Django's code is open source
    - Django's organization is managed by a non-profit
- [What is Tailwind CSS?](https://blog.hubspot.com/website/what-is-tailwind-css)
    - Utility-first CSS framework designed to enable users to create applications faster and easier
    - Advantages of Tailwind CSS:
        - Write less custom CSS
        - Keep CSS files small (dead-code elimination)
        - Don't have to invent class names
        - Localized CSS helps avoid modifying other CSS styles across the website
    - Disadvantages of Tailwind CSS:
        - Low-level framework
        - Doesn't offer fully styped components like Bootstrap buttons, dropdowns and navbars

## Bookmark and Review

- [What is Django](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Introduction)
- [First Django App - Part 1](https://docs.djangoproject.com/en/4.1/intro/tutorial01/)
- [First Django App - Part 2](https://docs.djangoproject.com/en/4.1/intro/tutorial02/)
- [Tailwind CSS Django - Flowbite](https://flowbite.com/docs/getting-started/django/)

## Reading Questions

### What are the key components of the Django framework, and how do they contribute to building a web application?

- Object-relational mapper: defines data models entirely in Python
- URLs and views: clean and elegant URL scheme
- Templates: easy-to-learn template designs
- Forms: handles user-submitted data
- Authentication: full-featured and secure authentication system
- Admin: provides production ready interface
- Internationalization: full support for translating to different languages and different customs
- Security: integrated protection features

### Explain the role of Django's MTV (Model-View-Template) architecture and how it handles a typical web request-response cycle.

- URLs: redirects HTTP requests to the appropriate view based on the URL request
- Models: Python objects that define the structure of an application data and provides mechanisms to manage and query a database
- View: request handler function which receives HTTP requests and returns HTTP responses
- Templates: text file defining the structure or layout

### What is the purpose of Tailwind CSS, and how does it differ from Bootstrap CSS?

Tailwind CSS is a low-level framework that allows developers to write less custom CSS than semantic CSS, dead-code elimination when shipped to production, advantage of removing the requirement to come up with creative class names, and localized CSS to help avoid changes to other CSS styles across the website. Tailwind CSS does not offer fully styled components like Bootstrap CSS, however it provides more flexibility and enables more style creativity

## Things I want to know more about

- Is Django used for the back-end or is it also used to develop the front-end?
- What advantages does Django have over building a web app in JavaScript using React + Node JS?
