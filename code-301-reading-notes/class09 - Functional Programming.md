# Class 09 - Functional Programming

## [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)
# The above article requires a paid subscription so I used these instead:
## [Functional Programming Concepts - Alternative](https://en.wikipedia.org/wiki/Functional_programming)
## [Advantages of Functional Programming](https://scalac.io/blog/unleashing-the-power-the-advantages-of-functional-programming-in-the-digital-age/)
- Functional programming is a programming practice that uses pure functions and avoids changing-state.
- A pure function produces the same output for the same set of input and does not affect state

### Questions

1. What is functional programming?
- Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data — Wikipedia
2. What is a pure function and how do we know if something is a pure function?
Two characteristics: deterministic and no side effects
 - Function produces same output for the same set of input everytime
 - Does not affect state or other variables
 - Example of pure function from ChatGPT:
    ```def add(a, b):```
    ```return a + b```
- Same output for every input and does not affect state
- Example of impure function from ChatGPT:
    ```total = 0```
    ```def impure_add(a):```
    ```global total```
    ```total += a```
    ```return total```
- This modifies state and produces a different output for every input so it is not a pure function
3. What are the benefits of a pure function?
- Enhanced code reusability and modularity, better scalability and performance optimization, reduced complexity and improved debugging
4. What is immutability?
- A concept that data's state cannot be changed or modified
5. What is Referential transparency?
- A function can be defined as referential transparent if it's output is solely determined by it's input parameters and calling the function will always produce the same results

## [Node.js Video Tutorial](https://www.youtube.com/watch?v=xHLd36QoS4k)
- Modules are JavaScript files that contain executable code and can be called somewhere else in the program.
Use ```require``` and ```module.exports``` to link the exported module to the file that is requiring the use of the code

### Questions

1. What is a module?
- Essentially another JavaScript file containing reuseable code that captures a specific functionality and can be executed somewhere elsej
2. What does the word ‘require’ do?
- It's essentially a call-back function and takes in the path of the module as a parameter to execute the code contained in the module
3. How do we bring another module into the file the we are working in?
- Use require and input the path of the module without the .js file type
- ex. ```let variable = require('./name-of-module');```
4. What do we have to do to make a module available?
- Inside of the module, explicitly state what part of the module we want available to the files that require this module
- Use ```module.exports = name-of-exported-function;```

## Things I want to know more about
- So prior to using React and state, have we been practicing functional programming for a majority of this class, but didn't know that's what we were doing because it wasn't defined yet?
- It seems like referential transparency and a pure function are the same thing, but is there any significant differences between the two concepts?
