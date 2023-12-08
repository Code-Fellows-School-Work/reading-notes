# Class 10 - In Memory Storage

## [Understanding the JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)

1. What is a ‘call’?
- Invoking a function
2. How many ‘calls’ can happen at once?
One at a time, top to bottom
3. What does LIFO mean?
- Last in, first out
4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

#### Answer from ChatGPT 
1. ```function multiply(a, b) {```
    ```return a * b;```
```}```

2. ```function add(a, b) {```
    ```return a + b;```
```}```

3. ```function main() {```

  ```let result1 = multiply(2, 3);```

  ```let result2 = add(result1, 4);```

  ```return result2;```
```}```

4. ```console.log(main());```

- Initial state of call stack is empty. 
- At 4. main is called at 3. and added to the call stack. 
- First variable at 3, calls the multiply function at 1. Multiply is added to the call stack. 
- Once multiply is complete, it's removed from the call stack and main remains.
- Second variable at 3, calls the add function at 2. Add is added to the call stack.
- Once add is complete, it's removed from the call stack and main remains. 
- result2 at 3 is returned to main and main is removed from the call stack.

5. What causes a Stack Overflow?
A function calls itself without an exit point 

## [JavaScript Error Messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c?gi=ee41dbe4b761)

### Questions

1. What is a ‘reference error’?
2. What is a ‘syntax error’?
3. What is a ‘range error’?
4. What is a ‘type error’?
5. What is a breakpoint?
6. What does the word ‘debugger’ do in your code?

## Things I want to know more about

