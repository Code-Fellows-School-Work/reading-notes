# Class 42 - Pythonisms

## Reading

- [Dunder Methods](https://dbader.org/blog/python-dunder-methods)
    - Explains numerous dunder methods for a python class 
    - Predefined methods used with classes like ```__init__``` or ```__str__```
    - Dunder methods let you emulate behavior of built-in types
        - len can be added as a method to a class: ```def __len__(self): return 42```
        - Then calling len on the object will return 42
        - slicing can be added using ```__getitem__```
- [Iterator](https://dbader.org/blog/python-iterators)
    - Step-by-step introduction on python iterators
    - Need both ```__iter__``` and ```__next__``` to allow iteration of a class object instance

- [Generators](https://dbader.org/blog/python-generators)
    - Generators perform a similar operation to iterators however they use a while statement and can reduce the amount of code required to iterate through a class object instance
    - A generator is more memory-efficient because it generates one value at a time rather than computing all values at onces then returning them

- [Decorators](https://realpython.com/primer-on-python-decorators/)
    - Function that takes another function and extends the behavior of the latter function without explicitly modifying it.
    - Provides a tutorial on how to define decorators on objects

## Videos

- [Optional: What are Python Generators](https://realpython.com/lessons/what-are-python-generators/)


## Reading Questions

### What are dunder methods in Python, and how do they allow for the customization of built-in behavior in classes? Provide an example of a common dunder method and its purpose.

    - Dunder methods are special methods that enhance and support classes in Python
    - They emulate access to built-in behavior to allow a python class to use a specific method on the object that isn't normally available
    - Common dunder methods are ```init```, ```str```, ```repr```, ```eq```, ```lt```

### Explain the concept of an iterator in Python. How do you create a custom iterator using the iter() and next() methods, and why are they important for enabling iteration in a class?

    - An iterator enables the operation of iterating through iterable objects
    - To create a custom iterator create a class method ```__iter__``` that returns self and ```__next__``` class method that includes the iteration code
    - ```__iter__``` enables the instance of the object to be iterable and ```__next__``` defines the behavior of the iteration operation

### What is a generator in Python, and how does it differ from a regular function? Illustrate your answer with an example of a generator function using the ‘yield’ keyword.

    - A generator is a function that iterates through an object one value at a time. It uses a ```yield``` keyword instead of ```return```
    - ChatGPT example:
<code> 

    def countdown(num):
        print("Starting countdown from", num)
        while num > 0:
            yield num
            num -= 1 

    for count in countdown(5):
    print(count)

</code>

### Define decorators in Python and explain their primary use case. How can you create and apply a custom decorator to a function or method? Provide a simple example to demonstrate this concept.

    - Decorators modify the behavior of a function or method
    - They're a function that wraps another function or methods within it and adds additional functionality before and after the wrapped function runs
    - ChatGPT example:

<code>

    def log_decorator(func):
        def wrapper(*args, **kwargs):
            print(f"Entering: {func.__name__}")
            result = func(*args, **kwargs)  # Call the original function
            print(f"Exiting: {func.__name__}")
            return result
        return wrapper

    @log_decorator
    def greet(name):
        print(f"Hello, {name}!")

    greet("Alice")

</code>

## Things I want to know more about

    - I would like some specifc examples and use cases for a decorator
