# Class 06 - Ten Thousand Game 1

## [How to use Random Module](https://www.pythonforbeginners.com/random/how-to-use-the-random-module-in-python)
- Random module provides access to functions to generate random numbers and strings
- ```randit()```: generate a random integer between the two arguments
- ```random()```: generate a random float between 0 an 1 (no arguments)
- ```choices()```: select a random element from a collection object and takes in a list, set, tuple, etc as an argument
- ```shuffle()```: shuffles the elements in the list and accepts a list as an argument
    - do not assign shuffle to a variable
- ```randrange()```: select a random elements from a given range.
    - takes three numbers as arguments for start, stop and step

## [What is Risk Analysis](https://www.edureka.co/blog/risk-analysis-in-software-testing/)
- In the context of software development, risk analysis is the process of identifying risks then prioritizing completion of each risk based on risk severity and impact to the project
- Steps to perform risk analysis:
    - Identify risk
    - Analyze impact to risk
    - Implement measures to mitigate risk

## [Test Coverage](https://martinfowler.com/bliki/TestCoverage.html)
- Tool to help find untested code within a codebase
- Devs focus on test coverage to ensure they are testing enough

## [Big O Notation](https://www.youtube.com/watch?v=v4cd1O4zkGw)

- Big O describes how time scales with respect to the input variable

- Summarizing the pigeon and internet transfer story:
    - Regardless of the data size, the pigeon needs to fly a specific distance
    - However, the amount of data vs time to transfer data is a linear function
    - Pigeon O(1) for constant time
    - Internet transfer O(N) where N = amount of data

- Big O rules:
    1. Different steps get added:
        - O(a) (step 1)
        - O(b) (step 2)
        - = O(a+b)
    2. Drop constants
        - O(2N) is actually O(N) 
    3. Different inputs => Different variables
        - It is not O(N^2) but instead O(a*b)
    4. Drop non-dominate terms
        - O(n+n^2) => O(n^2)
        - n^2 what really drives and dominates the rate of change 

## [Dependendcy Injection](https://www.freecodecamp.org/news/a-quick-intro-to-dependency-injection-what-it-is-and-when-to-use-it-7578c84fa88f/)
- Technique whereby one static object (or static method) supplies dependencies of another object

## Additional Resources

[Python Random Module](https://docs.python.org/3/library/random.html)

### Questions

1. How can the random module be utilized in Python to generate random numbers or make selections from a list, and what are some common functions available within the module?
    - The random module includes several functions that will select a random number or element within a list.
    - Common functions available include: ```randit()```, ```random()```, ```choice()```, ```shuffle()```, ```randrange()```

2. In the context of software development, what is risk analysis, and what are the key steps involved in conducting a risk analysis for a software project?
- Risk analysis is the process of identifying risks, assessing each risk, and implementing measures to mitigate risk
- Steps to conduct risk analysis:
    1. Identify risks
    2. Analyze risks
    3. Mitigate risks

3. What is test coverage and why is it an important (or potentially misleading) metric in software testing?
    - Test coverage is a tool to help identify how much code has been tested, however it can be misleading because getting 100% test coverage does not necessarily mean it covers all cases and if not careful, may result in bugs released to production

4. What is Big O notation, and how is it used to describe the performance of an algorithm? Give an example of an everyday task (not software related) that demonstrates O(n) time complexity.
    - Big O describes the efficiency of an algorithm based on the input size of data. 
    - When you check your mail, the amount of time it will take to open and read each envelope is directly proportional to the amount of mail you receive. For example, if one envelope to open and read takes 1 minute, then 100 envelopes will take 100 minutes to open and read.

## Things I want to know more about
- Why can't I assign a variable to the random function shuffle()? The description of the function says it shuffles the elements in place so does that have to do with why I can't:
    <pre>
    <code>
    import random
    fruits = ["apple", "banana", "cherry"]
    integer1 = random.shuffle(fruits)
    print(integer1)
    
    output = None
     </code>
     </pre>

