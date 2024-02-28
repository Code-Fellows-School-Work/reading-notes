# Class 38 - React 2

## Reading

- [React - Conditional Rendering](https://reactjs.org/docs/conditional-rendering.html)
    - Enables dynamic rendering of certain components if a specific action or condition is met
- [React - Lists & Keys](https://reactjs.org/docs/lists-and-keys.html)
    - Use map method and ```<li>``` element to traverse through an array and render as a list
    - Use keys to define unique IDs which help react identify which items have been changed
- [React - Forms](https://reactjs.org/docs/forms.html)
    - Provides examples on how to structure a form to include ```<input>```, ```<select>```, ```<textarea>```
- [React - Lifting State](https://reactjs.org/docs/lifting-state-up.html)
    - If several components need to use a shared state, then life the shared state to their closest common ancestor
    - This approach centralizes state and helps manage the state data flow
- [React - Composition vs Inheritance](https://reactjs.org/docs/composition-vs-inheritance.html)
    - React docs recommend using composition over inheritance to reuse code between components
- [Thinking in React](https://reactjs.org/docs/thinking-in-react.html)
    - Provides an example of how to develop a React App using the "Thinking in React" mindset

## Bookmark and Review

- [React - Comprehensive Guide](https://tylermcginnis.com/reactjs-tutorial-a-comprehensive-guide-to-building-apps-with-react/)
- [Heroicons](https://heroicons.com/)

## Reading Questions

### How does lifting state up in a React application help with managing data flow and what are the benefits of using this approach?

    - If two or more components require the use of a shared state, then lift state up to the most common ancestor
    - Centralizing state into one place makes it easier to track and manage changes because all state updates happen in one place rather than spread out across multiple components

### Explain the concept of conditional rendering in React and provide an example of how to implement it in a component.

    - Conditional rendering enables dynamic rendering of specific content when specific conditions are met
    - Use of the ternary operator, logical operator, or if and else statemenents are ways to implement conditional rendering

### What are the main principles behind "Thinking in React" and how do they guide the process of designing and building a React application?

    1. Start with a mock
    2. Build a static version in React
    3. Identify the minimal representation of UI state
    4. Identify where state should live
    5. Add inverse data flow

    - Building a React application using this structure leads to efficient development, easier maintenance and a more scalable application architecture

## Things I want to know more about

    - I don't understand the purpose of the special children prop
