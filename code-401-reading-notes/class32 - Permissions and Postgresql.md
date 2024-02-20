# Class 32 - Permissions & Postgresql

Description of the assignment

## Reading

- [DRF Permissions](https://www.django-rest-framework.org/api-guide/permissions/)
    - Permissions determine whether a request should be granted or denied access
    - Uses authentication information to determine if the request should be permitted
    - Each permission check is defined as classes
    - Object level permissions authorize access to certain objects within the system
    - Article also provides a tutorial on how to apply permissions in settings and example permission classes
- [Review SQL Prework](https://codefellows.github.io/common_curriculum/prework/SQL)
    - Structure Query Language (SQL)
    - SQL enables a user to create, use and manage a database
    - Also enables to perform queries and retrive data out of a database
    - Common databases are Oracle, SQL Server, MySQL, Sybase and PostgreSQL
    - Each is maintained by different organizations and optimized for different uses
    - Each has same basic syntax with varying differences in advanced syntax
    - A table is a database set of rows and columns and each row is an instance of the entity in the table and each column is a property of that instance
    - A database schema describes the structure of the table and the datatypes for each column
    - Basic SQL commands:
    ```INSERT: adds data```
    ```SELECT: retrieve data```
    ```DELETE: delete data```
    ```UPDATE: modify exisiting data```
    - Before updating and deleting a row of data, use a select and where statement to ensure you're targeting the correct row of data
    - Format for a SQL query
    1. SELECT statement specifies the data to be displayed
    2. FROM statement specifies the source of the data
    3. Optional statement to delcare how to transform the data

## Bookmark and Review

- [Classy Django REST](http://www.cdrf.co/)
- [DRF Generic Views](https://www.django-rest-framework.org/api-guide/generic-views/)
    - Developed as a shortcut to provide generic views for commonly used patterns

## Reading Questions

### What are the key components and purpose of Django Rest Framework (DRF) permissions, and how do they help in securing an API?

- Permission classes that define permission checks and object level permissions that authorize access to specific objects in the system
- Permissions help ensure APIs share resources to authorized users and prevent access to unauthorized users

### In SQL, what is the purpose of the SELECT statement, and how would you use it to retrieve all columns from a table called 'employees'?

- Select statement specifies the data to be displayed and you can either list out all the column names or use * to retrieve all information

### Can you explain the role of DRF Generic Views and provide examples of their usage in building a RESTful API?

- Provides pre-built views for commonly used CRUD patterns. The examples from the article are exactly the same views used in Lab 31 assignment
- Example from ChatGPT:

<code>

    from myapp.models import MyModel

    from myapp.serializers import MyModelSerializer

    from rest_framework.generics import ListAPIView

</code>
<code>

    class MyModelListView(ListAPIView):

        queryset = MyModel.objects.all()
        
        serializer_class = MyModelSerializer

</code>

## Things I want to know more about

> Can you use Auth0 to do the same thing as DRF permissions? Or does Auth0 only authorize or unauthorize access to an entire application?
