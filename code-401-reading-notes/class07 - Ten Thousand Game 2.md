# Class 07 - Ten Thousand 2

## [Python Scope](https://realpython.com/python-scope-legb-rule/)
- Scope defines the area in a program where variables, functions and objects are accessible.
    - Global: all variables, functions and objects are accessible throughout all the code
        - Can lead to code being unintentionally used or manipulated by other areas of the program
    - Nonlocal: restricts the use of code to a certain area of the program
    - In scope: Access a given name within a code
    - Out of scope: When a given name is unaccessible 
- ```globals()``` and ```locals()``` are functions that help identify names within a given scope
    - ```globals()``` returns a dictionary containing the names of all global functions prior to the function call
    - ```locals()``` when used within a codeblock, returns a dictionary containing the names of all local functions prior to the function call

## [Big O Notation](https://www.youtube.com/watch?v=dNorFNlDbX0)
- Describes the concent of eventuality and compares sequences with varying rate of change to determine which sequence will eventually be larger
- Common Big O examples from smallest rate of change to largest:
    - Constant: O(1)
    - Logarithmic: O(log n)
    - Polynomial: O(n^?)
    - Exponential: O(?^n)
    - Factorial: O(n!)

## Additional Resources
[Rolling Dice Example](https://web.archive.org/web/20220608035657/https://artofproblemsolving.com/wiki/index.php/Basic_Programming_With_Python#Random)

### Questions

1. Explain the concept of variable scope in Python and describe the difference between local and global scope. Provide an example illustrating the usage of both.
    - Global scope means any variable, function and object is accessible throughout all the code. 
    - Local scope means these variables, functions and objects are only accessible in a defined area of the program.
    - [Global and Local Illustration](/code-401-reading-notes/assets/Screenshot%202024-01-15%20112325.png)

2. How do the global and nonlocal keywords work in Python, and in what situations might you use them?
    - ```globals()``` returns a dictionary containing the names of all global functions prior to the function call
    - ```locals()``` when used within a codeblock, returns a dictionary containing the names of all local functions prior to the function call
    - They can be used to help with debugging 

3. In your own words, describe the purpose and importance of Big O notation in the context of algorithm analysis.
- Break down an algorithm's rate of change then compare that to the growth rate of a constant, logarithmic, polynomial, exponential, or factorial function to determine the algorithm's scalability as input size increases.

4. Based on the Rolling Dice Example, explain how you would simulate a dice roll using Python. Describe how you would use code to calculate the probability of rolling a specific number (e.g., the probability of rolling a 6) over a large number of trials.
- Import random library and define a function that uses the ranint function
- Initalize a counter and add to the counter the amount of times the ranint function output the integer 6
- Divide output amount by number of trials to calculate probability of rolling a 6

## Things I want to know more about
- What other use cases can I use ```globals()``` and ```locals()``` other than debugging?