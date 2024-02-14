# Readings: Django CRUD and Forms

## Reading

- [Django Forms](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Forms)
    - Forms collect information from users then later stored in a database
    - Forms use widgets to allow users to enter different data types to include text entry, checkboxes, radio buttons, data pickers, etc.
    - Django Forms takes care of the under-the-hood work and provides devs a framework to define forms and their fields, use objects to generate form HTML code, and handles validation and user interaction

## Bookmark and Review

- [Django Templates](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Home_page)
    - Text file that defines the stucture or layout of a file and uses placeholders to represent actual content
- [Django Views](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Generic_views)
    - Views handle the incoming HTTP requests and application responses

## Reading Questions

### How do Django Forms facilitate user input handling, and what are some key components of creating a form using the Django framework?

- Django Forms takes care of the under-the-hood work and will facilitate HTML form generate, data validation to ensure users input proper data, processes the data into the database, once all actions are complete, redirect the user to another page
- Key components of creating a form in the Django framework include the form class (defines the form structure), fields, widgets (text entry, checkboxes, radio buttons, etc) and validiation

### Explain the purpose of Django Templates in web development and describe how template inheritance can be utilized to improve code reusability and maintainability.

- Templates define the structure or layout of a file and uses placeholders to represent actual content
- Template inheritance allows Django projects to build a base template containing the overall structure and layout then child template will inherit the base and selectively override content. This reduces layout duplication, ensures standardization across multiple child templates and helps with scalability

### Describe the function of Django Views in handling HTTP requests, and outline the differences between function-based views and class-based views.

- Views handles HTTP requests, extract the relevant information from the request model or retrieve data from database models, execute application logic and creates responses
- Function-based views are Python funcctions that are simple to understand but lack built-in support for handling HTTP methods
- Class-based views inherit from django and offer built-in support for HTTP methods and provide reuseable functionality 

## Things I want to know more about

- How do you create the actual form on the home page instead of the admin page?
