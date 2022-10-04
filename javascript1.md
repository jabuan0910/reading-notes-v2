# Programming with JavaScript

### Day 7 - 10/4/22 - Code 102n65

## Today we learned about functions and operators in JavaScript programming

# Control Flow

### What is it?

* Its the order in which the computer executes statements in script.
* Code is the run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops.
* For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not:

'''
if (field==empty) {
    promptUser();
} else {
    submitForm();
}
'''

* A typical script in JavaScript or PHP (and the like) includes many control structures, including conditionals, loops and functions. Parts of a script may also be set to execute when events occur.

> See source [here](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow) for more information.

# JavaScript Functions

### What is it?

A JavaScript function is a block of code to perform a particular task. It is a function executed when "something" invokes it (calls it).

* An example of a function:
'''
function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
'''

### What is the function syntax for JavaScript?

Its defined with the `function` keyword, followed by a **name**, followed by parentheses **()**.

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas:
***(parameter1, parameter2, ...)***

The code to be executed, by the function, is placed inside curly brackets: **{}**

`
function ***name(parameter1, parameter2, parameter3)*** {
  // code to be executed
}
`

Function **parameters** are listed inside the parentheses () in the function definition.

Function **arguments** are the **values** received by the function when it is invoked.

Inside the function, the arguments (the parameters) behave as local variables.

> A Function is much the same as a Procedure or a Subroutine, in other programming languages.

For more information go [here](https://www.w3schools.com/js/js_operators.asp) to learn more.

# JavaScript Operators

What are they?

Arithmetic operators are the basic operators that we use to do sums in JavaScript:

| **Operator**            |      **Function** |
| :---: | :---: |
| `Addition +` | Adds numbers, ex. `let z = x +y;` |
| `Assignment =` | Assigns value to variable, ex. `let x = 10;` |
| `*` | Multiplies numbers |
| `-` | Subtracts numbers |
| `**` | Exponentiation, raises first operand to power of second operand, <br>ex. `let z = x ** 2;` result is `25` |
| `/`| Divides numbers |
| `%` | Division remainder|
| `++` | Increment |
| `--`| Decrement|
| `+=`| `x += y`, same as `x = x + y`|
| `let text3 = text1 + "" + text2;`| Concatenate strings |
| `let z = "Hello" + 5;`| Adds strings and numbers|

## Additonal Notes

## Lecture

Review:
use strict - tells us to follow some baseline 'strict rules'
**vars** will be seen, **let** is the most common used in the industry.

Learn more about operators [here](https://www.w3schools.com/js/js_operators.asp). Also, [here](https://www.w3schools.com/js/js_arithmetic.asp)

Back to [Home](https://jabuan0910.github.io/reading-notes-v2/)



Additional Notes:

'use strict';

<!-- // Logical Operators -->

// && Logical AND
// true && true

let response = prompt("Do you like javascript?");
if (response == 'yes' || response == 'YES'){
  console.og('Huzzah!');
}


<!-- STRUCTURE OF A FUNCTION -->

<!-- FUNCTION DECLARATION -->
 <!-- function functionName(parameters){code to be executed} -->

<!-- Example:

function addTwoNumbers(number1, number2,){
  console.log (number1 + number2);
  return number1 + number2;
}

addTwoNumbers("Hello", "world"); -->

Example 2:

function getName(){
  let userName = prompt("What is your name?");
  return userName;
}

let yourName = getName();

document.write("Hello and welcome," + userName);



getName();

