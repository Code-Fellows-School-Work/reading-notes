# Class 16 - Serverless Functions

## [What is Serverless Computing?](https://www.ibm.com/topics/serverless)

- Doesn't mean no servers -- they are essentially invisible to the developer because they're not responsible for managing it
- Enables developers to focus on the front-end and deploy their application to a cloud service provider that handles the back-end logic
- Provides a use-by-demand system that only spins up when there's a request for the service

## [venv - Creation of Virtual Environments](https://docs.python.org/3/library/venv.html)

- Contain all software libraries in a virtual container instead of downloading the software libraries onto the machine

## [Vercel - Get Started](https://vercel.com/docs/getting-started-with-vercel)

- Provides tools, workflow and processes to build and deploy web applications.

## [http.server](https://pymotw.com/3/http.server/index.html)

- Describes the base classes required for implementing a web server

## [Requests](https://requests.readthedocs.io/en/latest/)

- User Guide on how to implement requests to a web application

## [What is Serverless?](https://www.youtube.com/watch?v=vxJobGtqKVM)

- YouTube video describing the benefits of serverless
- Infrastructure management is not required because it's taken care of enabling the developer to focus on the business logic
- Enables teams to increase productivty and bring products to market faster

## Additional Resources

[Serverless Functions Overview](https://vercel.com/docs/functions/serverless-functions)

[Effective Python Environments](https://realpython.com/effective-python-environment/)

### Questions

1. What are the key characteristics of serverless computing, and how does it differ from traditional server-based architectures?

- Serverless computing enables the developer to focus on the front-end code instead of developing code for the back-end like for a traditional server. Additionally, serverless operates using a by-demand system where the serverless computing only runs if there's a request for a service whereas a traditional server is continuously operating

2. How can one get started with Vercel, and what are the main steps involved in deploying a serverless function using Vercel?

- Create an account, install ```pnpm i -g vercel```, use a template or import an exisiting project, add a domain, deploy project

3. What are APIs, and how can they be utilized in Python applications to access and manipulate data from external sources?

- Application programming interface that acts as a bridge between systems. They can intergrate a web application to a server or external database to access and manipulate data to display on the front-end

4. What is the Requests library in Python, and how can it be used to interact with APIs by sending HTTP requests? Can you provide an example of a basic GET request using the Requests library?

- Simplifies the process for using web APIs in Python. Use ```python -m pip install requests``` to first install.
Example from the reading: 
<pre>
<code>
    import requests
    response = requests.get("https://randomuser.me/api/")
    response.text
</code>
</pre>

## Things I want to know more about

- What does it mean to consume an API?