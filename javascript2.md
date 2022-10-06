# Operators and Loops

### Day 8 - 6/28/22 - Code 102n63

Today we have learn expressions, operators and Loops in JavaScript.

Main Focuses:

      * `Comparison operators/Assignment operators`
      * `for statement`
      * `while statement`

## Comparison operators

### What are comparison operators?

A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality.

Here is a following table which describes the comparison operators in terms of a sample code:

```
const var1 = 3;
const var2 = 4;
```

|          **Comparison operators**           |
| `Operator Description Examples returning true` |
| `Equal`(==)`Returns true if the operands are equal.` | `3 == var1` |
| `"3" == var1`|
| `3 == '3'`|
| `Not equal (!=) Returns true if the operands are not equal.` | `var1 != 4` |
| `var2 != "3"` |
| `Strict equal (===) Returns true if the operands are equal and of the same type. See also Object.is and sameness in JS. 3 === var1
Strict not equal (!==) Returns true if the operands are of the same type but not equal, or are of different type. var1 !== "3"
3 !== '3'
Greater than (>) Returns true if the left operand is greater than the right operand. var2 > var1
"12" > 2
Greater than or equal (>=) Returns true if the left operand is greater than or equal to the right operand. var2 >= var1
var1 >= 3
Less than (<) Returns true if the left operand is less than the right operand. var1 < var2
"2" < 12
Less than or equal (<=) Returns true if the left operand is less than or equal to the right operand. var1 <= var2
var2 <= 5

## Assignment Operators

An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal `(=)`, which assigns the value of its right operand to its left operand. That is, `x = f()` is an assignment expression that assigns the value of `f() to x`.

| **Operator**            |          **Function** |
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

| **Bitwise Assignment Operator**            |          **Function** |
| :---: | :---: |
| `&=` | AND |
| `|` | OR |
| `^=` | XOR |
| `<<` | Left shift|
| `>>` | Right shift |
| `>>>` | Unsigned right shift |

| **Logical Assignment Operator**            |          **Function** |
| :---: | :---: |
| `&&=` | AND |
| `||=` | OR |
| `??=` | XOR |

# Loops and iteration

### What are Loops?

Loops offer a quick and easy way to do something repeatedly.

You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop:

```
for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');
}
```

There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!)

## for statement

A `for` loop repeats until a specified condition evaluates to false. The JavaScript `for` loop is similar to the Java and C for loop.

For more information go [Here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#assignment_operators)

Back to [Home page](https://jabuan0910.github.io/reading-notes-v2/)





# Why Loops?
Loops are really helpful when you're trying to do someting
repeatedly

While loop -- generally when we don't know ahead of time how many loops we want

STRUCTURE: WHILE

while (condition to evaluate is true){
  execute this code
}

let response = prompt("What is my fav color?");
while (response !== 'yellow'){
  response =("Wrong! Guess again.")
}

console.log("Congrats, you guessed it!");

let i = 0;
while (true){
  console.log('hi');
  i++;
}

let x = 99
while(x < 100){
  console.log(x);
  x++;
}

# A FOR LOOP

for(initial; condition; increment){code to execute}

for(initial value; condition to evaluate; increment){
  code to execute
}

for (let i = 0; i < 10; i++){
  console.log(i);
}

i = 0 | 0 < 5? T | console.log 0 | i is 1
i = 1 | 1 < 5? T | console.log 1 | i is 2
i = 2 | 2 < 5? T | console.log 2 | is is 3


# WHY USE LOOPS?

Used when you don't know how many times the loop executes.

i = i + 1

# Operators and Loops

### Day 8 - 10/5/22 - Code 102n65

Today we have learn expressions, operators and Loops in JavaScript.

Main Focuses: 
    
      * `Comparison operators/Assignment operators`
      * `for statement`
      * `while statement`

## Comparison operators

### What are comparison operators?

A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality.

Here is a following table which describes the comparison operators in terms of a sample code:
```
const var1 = 3;
const var2 = 4;
```

|          **Comparison operators**           |
| `Operator Description Examples returning true` |
| `Equal`(==)`Returns true if the operands are equal.` | `3 == var1` |
| `"3" == var1`|
| `3 == '3'`|
| `Not equal (!=) Returns true if the operands are not equal.` | `var1 != 4` |
| `var2 != "3"` |
| `Strict equal (===) Returns true if the operands are equal and of the same type. See also Object.is and sameness in JS. 3 === var1
Strict not equal (!==) Returns true if the operands are of the same type but not equal, or are of different type. var1 !== "3"
3 !== '3'
Greater than (>) Returns true if the left operand is greater than the right operand. var2 > var1
"12" > 2
Greater than or equal (>=) Returns true if the left operand is greater than or equal to the right operand. var2 >= var1
var1 >= 3
Less than (<) Returns true if the left operand is less than the right operand. var1 < var2
"2" < 12
Less than or equal (<=) Returns true if the left operand is less than or equal to the right operand. var1 <= var2
var2 <= 5

## Assignment Operators

An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal `(=)`, which assigns the value of its right operand to its left operand. That is, `x = f()` is an assignment expression that assigns the value of `f() to x`.


| **Operator**            |          **Function** |
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

| **Bitwise Assignment Operator**            |          **Function** |
| :---: | :---: |
| `&=` | AND |
| `|` | OR |
| `^=` | XOR |
| `<<` | Left shift|
| `>>` | Right shift |
| `>>>` | Unsigned right shift |

| **Logical Assignment Operator**            |          **Function** |
| :---: | :---: |
| `&&=` | AND |
| `||=` | OR |
| `??=` | XOR |




# Loops and iteration

### What are Loops?

Loops offer a quick and easy way to do something repeatedly. 

You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop:
```
for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');
}
```
There are many different kinds of loops, but they all essentially do the same thing: they repeat an action some number of times. (Note that it's possible that number could be zero!)

## for statement

A `for` loop repeats until a specified condition evaluates to false. The JavaScript `for` loop is similar to the Java and C for loop.


For more information go [Here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#assignment_operators)



Back to [Home page](https://jabuan0910.github.io/reading-notes-v2/)

