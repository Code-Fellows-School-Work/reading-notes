# Class 08 - Ten Thousand 3

## [List Comprehension](https://www.pythonforbeginners.com/basics/list-comprehensions-in-python)
- A method to create and manage lists
- Used for simple list transformations
- Enables writing compact code using lesser lines

## [Primer on Decorators](https://realpython.com/primer-on-python-decorators/)
- You can pass a function as an arugment (exclude the ())
    - Doing so means you're passing a reference to the function instead of executing the function
</code>
</pre>
say_hello(hi_there)
</code>
</pre>
    - say_hello is the function
    - hi_there is a function being passed as an argument without ()
- Decorators wrap a function, modifiying its behavior
- Use the @function_name to inform Python what functions to reference for 
</code>
</pre>
def do_twice(func):
    def wrapper_do_twice():
        func()
        func()
    return wrapper_do_twice

@do_twice
func()

@do_twice
func
</code>
</pre>

### Questions

1. What is the basic syntax of Python list comprehension, and how does it differ from using a for loop to create a list? Provide an example of a list comprehension that squares the elements in a given list of integers.
<pre>
<code>
my_new_list = [ expression for item in iterable_object if condition]
</code>
</pre>
    - iterable_object = literal iterable object (list, tuple, set, etc)
    - item = item represents element
    - expression = mathematical expression or function
    - if condition = only output element to new list object if it meets a certain condition
- A for loop will use multiple lines of code for more complex operations whereas a list comprehension is used for more simple transformations
<pre>
<code>
original_list = [1, 2, 3, 4, 5]
new_list = [int**2 for int in original_list]
new_list = [1, 4, 9, 16, 25]
</code>
</pre>

2. What is a decorator in Python?
- A function that takes another function as an argument and modifies the argument function's behavior without modifying it

3. Explain the concept of decorators in Python. How do they work, and what are some common use cases for them? Provide an example of a simple decorator function from the reading.
- Decorators help add new functionality to an existing function by referencing other functions. Instead of an example from the reading, I found a more understandable example from [Youtube](https://www.youtube.com/watch?v=BE-L7xu8pO4)

## Things I want to know more about
- I think I understand the concept of a decorator but unsure about the implementation
