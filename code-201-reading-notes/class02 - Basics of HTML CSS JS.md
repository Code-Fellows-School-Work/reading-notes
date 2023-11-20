# Class 02 - Basics of HTML, CSS and JavaScript

## [HTML Fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)
HTML semantics describes the purpose of the content that it's enclosing. It adds structure to help format a webpage. It also helps for accessibility, search engine optimization and organizes content.
 - Some examples are header, nav, main, footer

## [Advanced Text Formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)
Additional methods to format HTML text are description lists, quotations, abbreviations, mark ups, super/subscrips, showing computer code, times and dates

### Questions

1. Why is it important to use semantic elements in our HTML?
- HTML semantics describes the purpose of the content that it's enclosing. It adds structure to help format a webpage. It also helps for accessibility, search engine optimization and organizes content.
2. How many levels of headings are there in HTML?
- 6 headings
3. What are some uses for the ```<sup>``` and ```<sub>``` elements?
- Sup can be used for dates like 1(st) or 4(th) or for mathematical notation like x^2
- Sub can be used for chemical notations for writing a chemical compound composition
4. When using the abbr element, what attribute must be added to provide the full expansion of the term?
- Add the title attribute ```<abbr title ="Hyper Text Markup Language">HTML.</abbr>```

## [How CSS is Structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)

CSS makes HTML look pretty and there are three ways to apply it:
1. External: applying external stylesheet which is the most common way to apply
2. Internal: stylesheet residing within an HTML document by placing a ```<style>``` element contained in the ```<head>```
3. Inline: styles that affect a single HTML element contained within a ```<style>``` attribute

### Questions

1. What are ways we can apply CSS to our HTML?
- External: applies external stylesheet and most common way, internal: stylesheet contained in the ```<head>``` element, inline: affects a single HTML element contained within a ```<style>``` attribute
2. Why should we avoid using inline styles?
- It's difficult to maintain because large styling changes may require multiple elements to be editted and all that extra code in the content makes it more difficult for review
3. Review the block of code below and answer the following questions:

   ```h2 {```
     ```color: black;```
     ```padding: 5px;```
   ```}```

1. What is representing the selector?
- H2
2. Which components are the CSS declarations?
- Property + value = delcaration so ```color``` (property): ```black``` (value) is one declaration and the other is ```padding: 5px```
3. Which components are considered properties?
- Color and padding

## [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
Additional things that can be conducted in JavaScript are adding comments using // in the line of code, operators for math and assigning values, creating if.. then statements for conditiional situations, creating functions to reuse lines of code, and events that receive input for a specific browser action and will output a specific code in response.

## Questions

1. What data type is a sequence of text enclosed in single quote marks?
- A string data type
2. List 4 types of JavaScript operators.
- Arithmetic (math operators), assignment (assigning variable), logical (AND, OR, NOT), comparison (ex. ```===```)
3. Describe a real world Problem you could solve with a Function.
- I've recently been doing home projects so I can use a function to calculate how much material I need for the amount of square footage of my home that needs repair. It would look similar to a math problem such as: total square feet * cost of material = total repair cost

## [Making Decisions in your Code - Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
JavaScript uses if... then statements to enable specific actions to be executed when a specific condition exists or occurs

## Questions

1. An if statement checks a __ and if it evaluates to ___, then the code block will execute.
- condition, true
2. What is the use of an ```else if```?
- Used in conjunction with a ```if... else``` statement to chain multiple ```if... else``` conditions
3. List 3 different types of comparison operators.
- ```===``` strictly equal
- ```!==``` strictly not equal
- ```<``` and ```>``` less than and greater than
4. What is the difference between the logical operator ```&&``` and ```||```?
- ```&&``` returns true if statements on both side of the operator are true. If one side is false or both sides are false, then the operator returns false - primarily used when both conditions needs to be true
- ```||``` returns true if at least one side of the operator returns true. If both sides are false, then the operator returns false - primarily used when at least one condition needs to be true

## [Writing a Good Git Commit Message](https://cbea.ms/git-commit/)
Best practices on writing good Git commit messages

## Things I want to know more about

- I personally do not like CSS so I want to learn more convenient methods to write CSS code to make the process simplier and easier
- More shortcuts for shorthand CSS in order to write cleaner CSS code
- if.. else statements and switch statements - practicing writing this code out practically