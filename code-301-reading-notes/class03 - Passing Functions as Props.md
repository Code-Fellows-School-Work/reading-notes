# Class 03 - Passing Functions as Props

## [React Docs - Lists and Keys](https://react.dev/learn#rendering-lists)
Use the `map` function to transform an array of products to redner lists of components.
Each `<li>` should have a unique ID to inform React what to do with the `<li>` in the event the item is inserted, deleted or reordered.

### Questions
1. What does .map() return?
- Transforms an array of products into an array of `<li>` items
2. If I want to loop through an array and display each value in JSX, how do I do that in React?
Use the `map` function
3. Each list item needs a unique ____.
- Database ID
4. What is the purpose of a key?
- A unique identifier so React knows what to do with the item in the event that items or inserted, deleted or reordered.

## [Spread Syntax](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)


### Questions

1. What is the spread operator?
- `...`
2. List 4 things that the spread operator can do.
- Copy an array
- Concatenate array
- Conditionally adding values to an array
- Copying and merging objects
3. Give an example of using the spread operator to combine two arrays.
`let array1 = [1, 2];`
`let array2 = [3, 4];`
`let combinedArray = [...array1, ...array2];`
Logging combinedArray to the console will output [1, 2, 3, 4]
4. Give an example of using the spread operator to add a new item to an array.
`let array1 = [1, 2];`
`let newArray = [...array1, 3];`
Logging newArray to the console will output [1, 2, 3]
5. Give an example of using the spread operator to combine two objects into one.
`let object1 = {firstName: 'Errol'};`
`let object2 = {lastName: 'Vidad'};`
`let combinedObject = {...object1, ...object2};`
Logging combinedObject to the console with output {firstName: 'Errol', lastName: 'Vidad'}

## [How to Pass a Function as a Prop](https://www.youtube.com/watch?v=n-6i_WGIOKE)


### Questions

1. In the video, what is the first step that the developer does to pass functions between components?
2. In your own words, what does the handleClick function do?
3. How can you pass a method from a parent component into a child component?
4. How does the child component invoke a method that was passed to it from a parent component?


## Additional Resources

## [React Docs - State and Lifecycle](https://legacy.reactjs.org/docs/state-and-lifecycle.html)

## [React Docs - Handling Events](https://legacy.reactjs.org/docs/handling-events.html)

## [React Tutorial Through "Developer Tools"](https://react.dev/learn/tutorial-tic-tac-toe)

## [React Boostrap Documentation](https://react-bootstrap.github.io/)

## [Bootstrap Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)

## [Bootstrap Shuffle - A Class "Sandbox"](https://bootstrapshuffle.com/classes)

## [Netlify](https://www.netlify.com/)

## Things I want to know more about
- Are there any special cases when using this.setState() is appropriate to use?
- I'd like to see additional examples of props and some considerations on why they're being used outside of the component instead of a state instead of the component.
