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

### Questions
1. What data types can you store inside of an Array?
- All the data types for example strings, numbers, boolean, objects, functions, etc.
2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

 ```const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];```
 
3. List five shorthand operators for assignment in javascript and describe what they do.
4. Read the code below and evaluate the last expression and explain what the result would be and why.

  ```let a = 10; ```
  ```let b = 'dog'; ```
  ```let c = false; ```

  // evaluate this 

 ```(a + c) + b;```
5. Describe a real world example of when a conditional statement should be used in a JavaScript program.
- fdsfs
6. Give an example of when a Loop is useful in JavaScript.
- fdsfds
