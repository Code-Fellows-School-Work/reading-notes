# Class 04 - HTML Links, JS Functions, and Intro to CSS Layout

## [Creating Hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

- Hyperlinks enable websites to link documents or other websites
- What I've done to my read-notes repository was added hyperlinks to all the reading websites
- A best practice for clear hyperlinks is to ensure the wording is descriptive

### Questions

1. To create a basic link, we wrap text or other content inside what element?
- Anchor element ex. ```<a href = "https://www.example.com">Visit Example.com</a>```
2. The href attribute contains what information?
- The URL
3. What are some ways we can ensure links on our pages are accessible to all readers?
- Using descriptive text, ensure the links visually standout, and use keywords that align with the linked text for search engine optimization

## [CSS - Normal Flow](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)
- Default appearance of a webpage without any styling code
- Beginning with normal flow allows developer to ensure content is well-structured and in a readable format prior to apply styling changes
- By default, each element will appear one after the other

## [CSS - Positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)
- Enables taking elements out of position and moving them into other positions
- Enables webpage creativity when moving content around and out of their normal position
- Different types of positioning is static, relative, absolute, fixed and sticky

### Questions

1. What is meant by “normal flow”?
- Default appearance of elements on a webpage without any CSS styling code applied
2. What are a few differences between block-level and inline elements?
- Block-level elements are laid out vertically whereas  inline elements all appear on the same line along with adjacent text content
3. ___ positioning is the default for every html element.
- Static
4. Name a few advantages to using absolute positioning on an element.
- Enables overlapping or to stack elements on each other
- Enables UI features that can be dragged and dropped anywhere on the page
5. What is a key difference between fixed positioning and absolute positioning?
- Fixed positioning fixes an element in place such that no matter how the webpage is scrolled, the element stays in the same position on the screen.
- Absolute positioning are positioned relative to nearest positioned ancestor element and may move as the webpage is scrolled

## [JS - Functions](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions)
- Functions store a piece of code and executes a single task
- Invoking a function means to execute (call) a code within a function
- Some functions require parameters as additional instructions for a function code otherwise the function may defer to a default parameter
- Anonymous function (ex. ```myFunction ()```) doesn't have a name and is generally how we've been writing code

### Questions

1. Describe the difference between a function declaration and a function invocation.
- Function declaration is defining a JS function whereas function invocation is directing a function to execute its code
2. What is the difference between a parameter and an argument?
- A parameter is the name of a value represented by the function (ex. ```let myFunction(age)``` where age is the parameter) whereas an argument is passed to the function when it is invoked (ex. ```myFunction(31) where 31 is the argument)

## [Misc - 6 Reasons for Pair Programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

- A software development practice where two developers work on one code. Several benefits include an additional set of eyes to catch code errors, increased collboration, allows an opportunity for a less-seasoned programmer to be mentored by a seasoned-programmer, helps develop social, interpersonal skills, and teamwork skills.

### Questions

1. Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.
- The mentorship opportunity while pair programming would be advantageous for me because pairing with a seasoned-programmer would essentially be a guide to help me write and understand code. Additionally, I would get a better sense of working in a software development environment and I'll have a better understand of the industry prior to working in it.

### Things I want to know more about
- How to use the div element because I think that's what I need to use along with other CSS commands to make content on my webpage appear side-by-side
- Examples of absolute and fixed positioning and how to implement on my webpage
- How to apply ```addEventListener()```on my webpage