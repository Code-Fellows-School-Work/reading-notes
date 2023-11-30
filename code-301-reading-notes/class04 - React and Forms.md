# Class 04 - React and Forms

## [How to Use Forms in React](https://www.robinwieruch.de/react-form/)
- An example of a form in a web application is a login form
- Another example is a web application where a user clicks the submit button with an attached event handler function
- Uncontrolled component does not control state whereas a controlled component does control state
- A form component recevies a callback handler from a parent component to use form data
- A form can be reset to its intial state after the user completes the form

### Questions
1. What is a ‘Controlled Component’?
- A controlled component is a form that has control over state whereas an uncontrolled component does not
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
- It depends on the application and if immediate user-feedback is required. Waiting to store into state responses until the form is submitted results in fewer state updates, but delayed feedback. Updating state with user responses provides immediate feedback, but more state updates.
3. How do we target what the user is entering if we have an event handler on an input field?
- Target the event object passed to the event handler function.

## [The Conditional (Ternary) Operator](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)


### Questions

1. Why would we use a ternary operator?
2. Rewrite the following statement using a ternary statement:

```if(x===y){```
  ```console.log(true);```
```} else {```
  ```console.log(false);```
```}```

## Additional Resources

## [React Bootstrap - Forms](https://react-bootstrap.github.io/docs/forms/overview/)

## [Conditional Rendering](https://react.dev/learn/conditional-rendering)

## Things I want to know more about

