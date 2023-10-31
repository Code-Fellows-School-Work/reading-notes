# Class 07 - Object-Oriented Programming, HTML Tables

## [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)
- Process of creating a representation for a problem within code and the model will describe factors that define and constrain the problem domain
- A well acritculated domain model can verify and validate the understanding of a problem
- This process is commonly referred to in a object-oriented model
- An example of using domain modeling to solve a real-world problem is calculating the popularity of epic fail videos --> determining the metric for popularity and creating self-contained objects with attributes and behaviors that target the metric  --> define a constructor and initalize properties -- > calculate and run the numbers

### Questions

1. Explain why we need domain modeling.
- It helps developers and relevant stakeholders understand the problem domain and breaks it down into an actionable process that is targetted and more effective to communicate.

## [HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)
- A table is a reference made up of rows and columns that stores values of different data types
- HTML tables are used for tabular data and not for HTML web page layouts 

### Questions

1. Why should tables not be used for page layouts?
- Reduces accessibility for visually impaired users
- Complex markup structure that makes coding difficult to structure and maintain
- Additional measures need to be implemented to ensure layout container's sizes change according to the size of their content (otherwise the container size would be non-adjustable or default to 100% size)
2. List and describe 3 different semantic HTML elements used in an HTML ```<table>```.
- ```<table>``` defines the entire table
- ```<td>``` defines the smallest container within a table
- ```<tr>``` defines table row
- ```<th>``` defines a header cell

## [JS Objects - Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)
- Constructors help code become DRY when multiple objects are created that use the same shape
- A constructor will create (construct) a new object, bind the new object to the constructor code, run the code and return a new object
- Conventionally, contructors being with a capital letter

### Questions

1. What is a constructor and what are some advantages to using it?
- A constructor helps make code more efficient in the case of needing to make multiple objects that use the same shape. They will construct a new object, bind the object, execute code and return a new object
2. How does the term  ```this ``` differ when used in an object literal versus when used in a constructor?
- ```this ``` for an object literal gives reference to the object whereas ```this ``` for a constructor gives references to the newly created object instance

## [Object Prototypes Using a Constructor](https://ui.dev/beginners-guide-to-javascript-prototype)
- Each object has a hidden property called prototype
- The prototype stores properties and methods shared among multiple objects
- Inheritance allows an object to inherit propertis and methods from another object
- Inheritance creates a relationship between objects enabling an object to resuse and extend its capabilities
- Ineritance is implemented through prototypes


### Questions

1. Explain prototypes and inheritance via an analogy from your previous work experience.
- When I first joined my previous company, I was a prototype that was inexperienced but possessed the basic skills and attributes required for my position. My first day, I met with HR and inheritted skills and knowledge regarding the company's core values, general office etiquette and company benefits. Overtime, I developed my level of knowledge and when my office hired a new employee, I had an oppotunity to share my skills and level of knowledge to the new employee so they can inherit those same skills and information I previously learned.

## Additional Resources

## [HTML Tables - Advanced and Accessibility](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)

## Thing I want to know more about
- I would like to see the domain modeling process in action from defining the problem domain, determining the metrics, writing the object-oriented codes, and running the numbers.
- How can I use a constructor to simplify the 5 objects I wrote in lab06
- I think I understand prototypes and ineritance via a simplified analogy but I would like to see a few examples of how to implement them in code to help solidify my understanding
