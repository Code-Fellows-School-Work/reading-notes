# Class 02 - State and Props

## [React Lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)
React component lifecycle consists of mounting, updating, and unmounting phases.
Mounting phase: component goes through constructor, render, and componentDidMount events.
Updating phase: components can re-render based on methods invoked like shouldComponentUpdate, render, and componentDidUpdate.
Unmounting phase: componentWillUnmount event will trigger to remove the component from the DOM.

### Questions

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
- Render
2. What is the very first thing to happen in the lifecycle of React?
- Mounting phase where an instance of a component is created then inserted into the DOM
3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
Constructor => render => componentDidMount => React Updates => componentWillUnmount
4. What does componentDidMount do?
- Invoked immediately after a component is mounted 

## [Youtube - React State vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)
Props are used to pass data to a component while state is used to manage and store dynamic data within a component. State enables updates to the application and re-renders based on response to user interaction.

### Questions

1. What types of things can you pass in the props?
- Props are like arguments and will pass things that initalize a function
2. What is the big difference between props and state?
- Props are handled outside and passed into a component and state is handled inside the component
- Any updates to state are handled inside the component and any updates to props are handled outside the component
3. When do we re-render our application?
- When there is a change in the application based on what the user has done.
4. What are some examples of things that we could store in state?
- Values in forms, counters, data.


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
