# Class 03 - HTML Lists, Control Flow with JS, and the CSS Box Model

## [Ordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
- Represents a numbered list typically read in order. 

## [Unorderd Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)
- Represents a list where items in the list do not need to be conducted or necessarily read in order.

### Questions
1. When should you use an unordered list in your HTML document?
- A collection of items that does not require a numerical ordering.
2. How do you change the bullet style of unordered list items?
- Apply a CSS code and use ```li {list-style-type}: enter_type;}```
3. When should you use an ordered list vs an unorder list in your HTML document?
- If the order of the listed items matter for example a receipe or directions.
4. Describe two ways you can change the numbers on list items provided by an ordered list?
- Add the attribute ```type="i"``` to change the numbers to roman numeral and use the start attribute ```start="enter_number"``` to begin the list at the value of enter_number

## [The Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
- Every feature of a webpage is contained within a box and malipulatin the size and characteristics of those boxes enables creative and complex webpage designs.

### Questions
1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
- The castle wall for a castle is the margin and the padding is the space for the people (or content) within the castle wall. As the population of the people grows, they will need more space to expand and therefore will need more padding in order to live happy. If the castle wall or the margin doesn't expand in relation to the size of the population, then everything inside the castle wall will be cramped, however the margin needs to be aware of it's size and not creep into other kingdoms or areas where the castle walls don't belong. Padding and margin need to work together in order to ensure the contents are happy and the castle walls are a reasonable size.
2. List and describe the four parts of an HTML elements box as referred to by the box model.
- Content: area where content is displayed
- Padding: area surronding the content as white space
- Border: area containing content and padding
- Margin: outermost layer that contains the remaining three parts

## [Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
- Used to store a list of items within a single variable
## [Operators and Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
- An expression is a sort of equation that solves to a value and the operator is the action or calculation between two or more values 
## [Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
JavaScript uses if... then statements to enable specific actions to be executed when a specific condition exists or occurs
## [Loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)
Loops are code that executes a certain task or action over and over again

### Questions
1. What data types can you store inside of an Array?
- All the data types for example strings, numbers, boolean, objects, functions, etc.
2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

 ```const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];```

- It doesn't look like a complete array because it's missing the variable assignments but based on the pattern, I assume the variable assignments are:
- ```const name```
- ```const age```
- ```const profession```
- ```const hobbies```
- Therefore you would access the values by recalling the appropriate variable with the number item in the array
 
3. List five shorthand operators for assignment in javascript and describe what they do.
- Assignment  ```x = f() ``` =  ```x =  f() ``` - assign a value to a variable
- Addition assignment ```x += f() ``` =  ```x = x + f() ``` - performs addition or concatination for strings and assigns result to the left operand
- Subtration assignment  ```x -= f() ``` =  ```x = x - f() ``` - performs subtraction and assigns result to the left operand
- Multiplication assignment ```x *= f() ``` =  ```x = x * f() ``` - performs multiplication and assigns results to the left operand
- Division  assignment ```x /= f() ``` =  ```x = x / f() ``` - performs division and assigns results to the left operand
- 
4. Read the code below and evaluate the last expression and explain what the result would be and why.

  ```let a = 10; ```
  ```let b = 'dog'; ```
  ```let c = false; ```

  // evaluate this 

 ```(a + c) + b;```

 - JS converts false to 0 so starting with order of operations, 10 + 0 = 10, then 10 + the string dog is a concatination to 10dog. So the final result is 10dog.
5. Describe a real world example of when a conditional statement should be used in a JavaScript program.
- If prompting the user to answer a yes or no question and the developer wants to respond with a specific response to yes and a specific response to no
6. Give an example of when a Loop is useful in JavaScript.
- If you want to perform a simple mathematical equation multiple times. Writing a loop code would be more efficient because it will reduce the amount of code written as opposed to individually writing out code equal to the amount of times that code should be executed.

### Things I want to know more about
- Shorthand operators is challenging to wrap my head around. I would like to see some in class examples
- I don't understand everything underneath division assignment in the expression and operators shorthand list