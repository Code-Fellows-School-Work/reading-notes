# Class 06 - Problem Domain, Objects, and the DOM

## [JS Objects](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)
- An object is a collection of related data or functionality
- Objects consist of serveral variables (properties) and functions (methods)
- Each object is made up of multiple items and each has a name paired with a value:
- Syntax ex. ``` let objectName = {```
                    ```Name1: Value1;```
                    ```Name2: Value2;```
                    ```Name3: Value3;```
```};```
- Dot notation and bracket notations are ways to access object properties
- Dot notation ex. ```objectName.Name1;```
- Bracket notation ex.  ```objectName["Name1];```

### Questions

1. How would you describe an object to a non-technical friend you grew up with?
- An object is like a storage box that contains multiple items within it and on the otherside of the box, there are labels (like properties) that describe the items stored within the box. 
- Another example would be a book (object), and it has the following properties: title, author, pages, genre 
2. What are some advantages to creating object literals?
-  The object is simplier to read and you can use dot notation (ex.: ```objectName.Name1```) to access properties and methods
3. How do objects differ from arrays?
-  Objects follow a name and value pair structure and accessing an object's properties are done through dot and bracket notation whereas arrays have values associated with indices and to access the array elements, you would use numeric indices like arrayName[0]
4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
- Bracket notation must be used when an object property name is held in a variable or if the property name is dynamic
5. Evaluate the code below. What does the term ```this``` refer to and what is the advantage to using ```this```?

    ```const dog = {```

    ```name: 'Spot',```

    ```age: 2,```

    ```color: 'white with black spots',```

    ```humanAge: function (){```

    ```console.log(`${this.name} is ${this.age*7} in human years`);```

    ```}```

    ```}```
- This refers to the object named dog and ```this``` gives reference to the object

## [Introduction to DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
- Document Object Model (DOM) - a programming interface for web documents

### Questions
1. What is the DOM?
- Document Object Model that represents the content of an XML or HTML document into a tree structure
2. Briefly describe the relationship between the DOM and JavaScript.
- JS is a programming language used to interact with the DOM

## Additional Resources

## [How to Solve Programming Problems](https://simpleprogrammer.com/solving-problems-breaking-it-down/)

## [Difference Between Primitive Values and Object References in JS](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)

## Things I want to know
- So does removing the function () piece from a method make it an object literal? 
- this. is hard to wrap my head around
- So DOM in other words is the bridge that connects developers to the webpage?