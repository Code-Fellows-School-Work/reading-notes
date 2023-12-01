# Class 05 - Putting it all Together

## [React Docs - Thinking in React](https://react.dev/learn/thinking-in-react)
General steps to building a React application: 
1. Break it apart into components
2. Describe each component's visual state
3. Connect components so data flows through them

Steps to implement a UI in React:
1. Break UI into a component hierarchy
2. Build a static version in React
3. Find the minimal but complete representation of UI state
4. Identify where your state should live
5. Add inverse data flow

### Questions
1. What is the ```single responsibility principle``` and how does it apply to components?
- In step 1 of implementing a UI in React, ```single responsibility principle``` recommends a component should only do one thing
2. What does it mean to build a ‘static’ version of your application?
- Building a version without interactivity (make it boring)
3. Once you have a static application, what do you need to add?
- Add state to allow users to interact with data
4. What are the three questions you can ask to determine if something is state?
    1. Identify every component that renders something using state
    2. Find the closest common parent component
    3. Decide where state lives
5. How can you identify where state needs to live?
    - Typically in common parent
    - Sometimes in some component above their parent component
    - Within a newly created state component 

## [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)
A higher-order function is a function that takes in a function as an argument and or returns a function
Examples of higher-order functions: map, filter, reduce, forEach, sort

### Questions
1. What is a “higher-order function”?
- A function that accepts a function as an argument and or returns a function
2. Explore the ```greaterThan``` function as defined in the reading. In your own words, what is line 2 of this function doing?
- Line 2 sets up a comparison function to check if a variable m is greater than a variable n
3. Explain how either ```map``` or ```reduce``` operates, with regards to higher-order functions.
- Both map and reduce use a callback function as an argument and they will apply the callback function to each element of an array

## Things I want to know more about
- It seems like one advantage of higher-order functions is to simplify code to be more readable and efficient. Are there any additional advantages or even limitations to using them?
- I need to increase my understanding about state. It seems like it's going to continue being a critical component in the upcoming projects.
