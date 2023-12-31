# Class 10 - Debugging

## [Troubleshooting JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong)
- Syntax error: spelling errors in code
- Logic error: Program runs but produces incorrect results
- Error message - "... is not a function" means JavaScript does not recognize the function probably because of a syntax error
- Error message - "can't access property "textContent", then use console.log following the line after the line of code that is producing the error and review what variable is being referenced
- Using console.log can also help troubleshoot a logic error
- [JavaScript Error Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)

### Questions
1. Name some key differences between a Syntax Error and a Logic Error.
- A syntax error means JavaScript does not understand the line of code typically from a spelling error and logic error means the code runs but does not produce the intended results
2. List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.
- I've seen the "... is not a function" before and "can't access property" but instead of using the developer tools recommended in this reading, I referred to ChatGPT to identify the erorrs in my code.
3. How will this topic continue to influence your long term goals?
- This will be helpful in making debugging more efficient and less painful. Understanding what capabilities of these debugging tools with help reduce the amount of time troubleshooting code and will help with project completion

## [Browser Developer Tools](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Tools_and_setup/What_are_browser_developer_tools#the_javascript_debugger)
- Browser Developer tools enables inspection of currently-loaded HTML, CSS and JavaScript on the webpage
- They can also be used to modify the current lines of code to preview the changes on the webpage 
- I've seened HTML and CSS modified using developer tools
- JavaScript has dev tools to select a point to run code up to called a breakpoint

### Questions
1. How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?
The debugger tool allows you to see under-the-hood of your HTML, CSS and JS files so you can identify issues with your code and also modify the code and review how the browser will respond to that updated code.
2. Define what a breakpoint is.
- A browser dev tool used to pause the execution of JavaScript code at a specific point to help troubleshoot or identify issues in code
3. What is the call stack?
- Identifies what code is used to get to the current line

## Additional Resources

## [Debugging HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Debugging_HTML)

## [Debugging CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Debugging_CSS)

## Things I want to know more about
- Are there any more types of error codes or is it just syntax or logic?
- Do different browser have different browser dev tools? Or are they all the same?
