# JavaScript

### Day 6 - 10/2 - Code 102

We have learned JavaScript today in relation to variables and what the content of the code looks like. In a nutshell, its a dynamic language that gives interaction for a website that are coded with certain expressions and variables. Its like having interactive muscles for both html and css in order to move.  Consistently, there is a quite a bit of logic that's put into it.

Reading Assignment: Start with variables. Look at the content and code. Get familiar and read through documentation for 45 minutes.

## What is JavaScript?

JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles.

## There are some key features in detail that includes features of JavaScript to make the language work, such as variables, strings, numbers and arrays

# Variables

### What are they?

Variables are containers for storing data or storing data values. They are expressions that hold values like in algebra.

There are 4 ways to Declare a JavaScript variable:

* var
* let
* const
* nothing

Examples:  
  > var x = 5;
  > var y = 6;
  > var z = x + y;

* x, y and z are variables, declared as **var** keyword.

Examples:
  >let x = 5;
  >let y = 6;
  >let z = x + y;

* x, y, and z are variable declared as **let** keyword.

Examples:
  > x = 5;
  > y = 6;
  > y = x + y;

* x, y, and z are undeclared variables.

In order to use **const** and how to use it?
  >As a general rule, it can always declare **variables** as *const*.
  >If the variable can change, then use **let**.

Examples:
  >const price1 = 5;
  >const price2 = 6;
  >let total = price1 + price2;

* As the two variables *price1* and *price2* are declared with const keyword. These values cannot be changed.
* As the variable **total** is declared with the **let** keyword. This value can be changed.

All javascript variables must be identified with unique names. These unique names would be called *identifiers*.
> Examples of identifiers can be short names (like x and y) or more descriptive names (age, sum, totalVolume).

General rules for constructing names for variables (unique identifiers) are:

* Names can contain letters, digits, underscores, and dollar signs.
* Names must begin with a letter
* Names can also begin with $ and_
* Names are case sensitive (y and Y are different variables)
* Reserved words (like JavaScript keywords) cannot be used as names

> **Note**: JavaScript identifiers are case-sensitive.

# Data Types

* Numbers
* Strings
* Booleans
* NaN
* Undefined

> You can learn more about JavaScript [here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/About_JavaScript)]



# Additional notes:

Console.log() = its essentially logging or writing to a console some text to validate

## What is Javascipt?

Variable are just labels/container for storing data

*Declaring a variable AND assigning value
let myName = "James"
*
let kitchenBox;

## Data Types

* Strings --> Text
  * 'Your text goes here'
  *'42'
* Numbers --> No quotation marks
  *42
* Booleans
  * True
  * False

## GETTING INPUT FROM USER

`prompt("Ask your question here")`
prompt("What is your name?");

Question: Option alt?

## Conditional logic

* `if(this condition is true){execute whatever code }

* If 
* Else if
* Else

* Two equals mean loosely the same
* Three equals strictly the same