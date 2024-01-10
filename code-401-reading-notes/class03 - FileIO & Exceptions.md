# Class 03 - FileIO & Exceptions

## [Read & Write Files in Python](https://realpython.com/read-write-files-python/)
- A file has 3 parts, header (metadata), contents, and end of file (file extension)
- Article describes how to navigate through file paths
- To open a file in python, use the built in function ```open()``` and assign it to a variable:
    - ```file = open('dog_breeds.txt')```
- This method requires a follow on close function:
    - ```file.close()```
- Recommended practice is using a ```with``` statement
    - ```with open('dog_breeds.txt') as reader: ```
- Second argument in the ```open()``` function is called mode and typically is set to 'r' for read
    - ```with open('dog_breeds.txt', 'r') as reader: ```
- After opening the file, you can read the file
    - Use ```.read()``` method to read the entire file
    - ```print(reader.read())``` will print the entire dog_breed.txt
    - There are other arguments that can be passed in to manipulate how the ```.read()``` method operates and there are other read methods
- After opening the file, you can write in the file
    - Replace second argument in open function with 'w' to write 
    - ```with open('dog_breeds.txt', 'w') as reader: ```
    - Use the ```.write(string)``` method and replace string to write in the file

[Exceptions in Python](https://realpython.com/python-exceptions/)
- Raising an exception is a tactic to help provide more detail to an error
    - Syntactically looks like this:
        - ```raise Exception(string)```

- An assertion error is another exception
    - Syntactically looks like this:
        - ```assert('linux' in sys.platform), string```
        - From the article example, this code should only work on linux systems and will throw an error on other systems

- Try and except block is used to catch and handle exceptions
    - Syntactically looks like this:
        <pre>
        <code>
        try: 
            with open('file.log') as file:
                read_data = file.read()
        except:
            print('Could not open file.log')
        </code>
        </pre>

- Additional statements that can be added is:
    - Else: No exceptions, then run this code
    - Finally: Always run this code

- Summary of exceptions from article:
    - ```raise``` allows you to throw an exception at any time.
    - ```assert``` enables you to verify if a certain condition is met and throw an exception if it isn’t.
    - In the ```try``` clause, all statements are executed until an exception is encountered.
    - ```except``` is used to catch and handle the exception(s) that are encountered in the try clause.
    - ```else``` lets you code sections that should run only when no exceptions are encountered in the try clause.
    - ```finally``` enables you to execute sections of code that should always run, with or without any previously encountered exceptions.

## [Python Tutorial: File Objects - Reading and Writing to Files](https://www.youtube.com/watch?v=Uh2ebFW8OYM)
- Youtube tutorial on how to read and write to files

## Additional Resources

[Reading and Writing Files in Python Quiz](https://realpython.com/quizzes/read-write-files-python/)

### Questions
1. What is the purpose of the ‘with’ statement when opening a file in Python, and how does it help manage resources while reading and writing files?
    - The with statement automatically closes the file after leaving the with code block. Closing a file helps avoid unwanted behaviors like resource leaks

2. Explain the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python. Provide examples of when to use each method.
    - Read method reads based on the number of size bytes while readline method reads size number of characters from that line.
        - Read method is useful for reading the entire file and typically used for smaller files
        - Readline method is useful for extracting certain information from a file instead of reading the entire file

3. Briefly describe the concept of exception handling in Python. How can the ‘try’, ‘except’, and ‘finally’ blocks be used to handle exceptions and ensure proper execution of code? Provide a simple example.
    - Try will tell the interpreter to run this line of code, but if that code doesn't run, then execute the line of code in except. And regardless if the try code or except code ran, the code in finally will always run.
        <pre>
        <code>
        try: 
            print(file)
        except:
            print('Could not open file')
        finally:
            print('This code will run regardless if file is printed or not')
        </code>
        </pre>

## Things I want to know more about
- Why do I need to close an open file?
- Are exceptions just a helpful tool for debugging or are there other practical applications for it?
