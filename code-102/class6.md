# Class 6 Notes - Activate Web Pages with Javascript

## Answer

1. What are variables in JavaScript? -  container of information
2. What does it mean to declare a variable? - creates a name for a container to store data
3. What is an “assignment” operator, and what does it do? - assigns a value to a variable
4. What is information received from the user called? - input from the user

## Class Notes

// Variables 

// Variable is a container for information (data)

// 4 ways to declare a variable

// 1:let can be changed
// 2:const cannot be changed
// 3: var <-- don't use
// 4: (none) <-- don't use

const myName = 'Errol';

let myAge = 34;
// birthday day happens
myAge = 35;

// Data type - has quotation marks
// strings: text - has quotation marks
// boolean: True or false
// number: no quotation marks

// assignment operator
let x = 5
let y = 10

// == loosely equivalent, data types do not need to match
// === strictly equivalent, data types must match

// x == y (FALSE)

//conditional logic

//if (this is true) {execute this code}

let x = 5
let y = 10

if (x == y) {
    console.log('Yes it is');
 }
else {
    consolve.log('No it isnt');