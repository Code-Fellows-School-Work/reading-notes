# Class 02 - Testing and Modules

## [In Tests We Trust - TDD with Python](https://code.likeagirl.io/in-tests-we-trust-tdd-with-python-af69f47e6932)
- Software development strategy designed around writing tests first then writing minimum code to pass the test
- Organize tests into a separate folder and name the py file as test_(name_of_module_tested).py

## [If name equals main](https://www.geeksforgeeks.org/what-does-the-if-__name__-__main__-do/)
- A module is a file containing Python definitions and statements
- A script is a set of instructions or commands
- Every Python module has it's __name__ defined
- ```if __name__ == '__main__'```: this implies the module is being run standalone
- If you import a script as a module, then ```__name__``` is set to the name of the script/module
    - Importing a script as a module will bring in the functionality from that script into another script
    - It's simply borrowing code from another file
- ChatGPT ex.
    <pre>
    <code>
    # main_script.py
    def say_hello(name):
        return f"Hello, {name}!"
    if __name__ == '__main__':
        print("This will only run if my_module is executed directly.")
    </code>
    </pre>

    <pre>
    <code>
    # main_script.py
    import my_module
    # Now you can use the functions and variables from my_module
    result = my_module.say_hello("Alice")
    print(result)
    </code>
    </pre>



## [Recursion](https://www.geeksforgeeks.org/introduction-to-recursion-data-structure-and-algorithm-tutorials/)
- The process in which a function calls itself directly or indirectly
    - Called a recursive function
- Adv: reduce the length of code 
- Perform the same operation multiple times with different outputs
- Steps for implementing recursion in a function:
    1. Define a base case: Identify the simpliest solution as the stopping condition and the prevent it from infinitely calling itself
    2. Define a recursive case: Define the problem in terms of smaller subproblems and call the recursive problem to solve each subproblem
    3. Ensure the recursion terminates by eventually reaching the base case
    4. Combine the solutions of the subproblems to solve original problem
- This about the finding a key within a box of boxes example from the prework

## [What on Earth is Recurion?](https://www.youtube.com/watch?v=Mv9NEXX1VHc)
- Another explaination of recursion in video form

## Additional Resources

[Google for Education: Python Lists](https://developers.google.com/edu/python/lists)

[Google for Education: Python Strings](https://developers.google.com/edu/python/strings)

[Python Modules and Packages](https://realpython.com/python-modules-packages/)

[Pytest Documentation](https://docs.pytest.org/en/latest/)

[Pytest Tutorial](https://www.guru99.com/pytest-tutorial.html)

### Questions
1. What are the key principles of Test-Driven Development (TDD) in Python, and how do they contribute to the overall quality of code?
    1.  Write a unit test and make it fail (the code isn't there yet)
    2.  Write the minimum amount of code to pass the test
    3.  Refactor the code and frequently check to ensure the code still passes. 
    - These steps help developers focus small so that they meet the required functionality while avoiding any unexpected coding issues 

2. Explain the purpose of the ```if __name__ == '__main__'```: statement in Python scripts. What are some use cases for including this conditional in your code?
- This informs the Python compiler if the Python Script is stand-alopne or if it's being imported into another script
- It allows to be selective of certain code blocks if they will run within a main application or borrowed elsewhere

3. Describe the concept of recursion in Python.
- A function that calls itself. It's purpose is to break down a large problem into smaller sub-problems and will perform the same operation multiple times with varying outputs.

4. What is the difference between Python modules and packages? Explain how to create, import, and use them in your Python programs.
- Module: A single file of Python code containing functions, classes and variables
    - Create: create a module by creating a .py file 
    - Import: import using ```import "module_name"```
- Package: An organization method to group related modules
    - Create: organize modules into a directory and include a ```__init__.py``` file
    - Import: import using ```from "package_name" import module_name"```

## Things I want to know more about

- What is the lib ```py test```