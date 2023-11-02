# Class 09 - HTML Forms and JavaScript Events

## [Web Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)
- Main interaction point between the user and a website and application
- Forms enable users to input data, the web server processes and stores the data, the the user will see some sort of page update as the output
- ```Input``` element is used to create a form control (multi-line text fields, dropdown boxes, button, checkboxes, etc)
- Form controls can use data validation to control input data type
- ``` Form ``` element starts the form and is a container for the remaining elements like ```label```, ```input```, ```textarea```, ```button```
```Action```, and ```method``` are additional attirbutes that direct where to store the data and what http method is used for sending data respectively

## [How to Structure Web Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)
- HTML markup is used to structure forms
- Common practice: wrap a label or widget within a list or using ```p``` or ```div``` elements
- Common practice: use HTML titles like ```h1``` or ```h2```
- Ensure the forms are designed with accessibility in mind 

### Questions
1. Why are forms so important in web development?
- Forms are important because it allows users to dyanmically update webpage content, it can be used to store input data and ensures input data is the correct data type.
2. When designing a form, what are some key things to keep in mind when it comes to user experience?
- Keeping it simple in order to make it easy for the user to use
3. List 5 form elements and explain their importance.
- ```Form``` begins the web form and is a container for the remaining elements
- ```Label``` provides a text description of the form field
- ```Input``` allows users to enter information or data
- ```Textarea``` allows user to enter longer-form text input
- ```Button``` allows user to submit data

## [Intro to Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)
- Events are instances or occurances that trigger JavaScript code
- An event handler is something attached to a block of code 
that ties the event to JavaScript code
- When an event is run, it's referred to as registering an event handler
- Event objects are specified using ```event```, ```evt```, or ```e``` (or really any name but those are commonly used) and target is used to reference the event to the element
- Event bubbling and capturing refers to the order of event propagation. Bubbling occurs on a nested element and continues to executing up the ancestor elements whereas capturing begins at the ancestor element and works down to the nested element

### Questions
1. How would you describe events to a non-technical friend?
- Events are triggers that cause things to happen. For example, if you press a button for the elevator, then a elevator will move to your floor and the doors will open
2. When using the addEventListener() method, what 2 arguments will you need to provide?
- Event type that specifies the type of event to be listened to and the name of the JavaScript function
3. Describe the event object. Why is the target within the event object useful?
- Event object provides information about the event that occurred and the event target ties the event to the HTML element
4. What is the difference between event bubbling and event capturing?
- Bubbling and capturing refers to the order of event propagation. Bubbling begins from the nested element and works its way up through the ancestered elements whereas capturing reverses the order and begins with the ancestered element and works its way down to the nested element

## Additional Resources

## [HTML5 Input Types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)

## [Event Reference](https://developer.mozilla.org/en-US/docs/Web/Events)

## Things I want to know more about
- Examples on how to implement events in the cookie-stand lab
- Seeing event bubbling and capturing in a use case example
- The process of determining how to plan and design a web form
