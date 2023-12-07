# Class 09 - Functional Programming

## [Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)
# The above article requires a paid subscription so I used these instead:
## [Functional Programming Concepts - Alternative](https://en.wikipedia.org/wiki/Functional_programming)
## [Advantages of Functional Programming](https://scalac.io/blog/unleashing-the-power-the-advantages-of-functional-programming-in-the-digital-age/)

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

### Questions

1. What is a module?
2. What does the word ‘require’ do?
3. How do we bring another module into the file the we are working in?
4. What do we have to do to make a module available?


## Things I want to know more about
- So prior to using React and state, have we been practicing functional programming for a majority of this class, but didn't know that's what we were doing because it wasn't defined yet?
- It seems like referential transparency and a pure function are the same thing, but is there any significant differences between the two concepts?
