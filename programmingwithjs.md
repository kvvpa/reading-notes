
# Programming with Javascript

##### 6/27/22 - Code 102 - Day Seven

## Control Flow

* Control Flow is the order the computer executes statements in a script.
* Run from first line to the last save for conditional structures such as if...else statements, functions, and loops.
* When you read a script, you can't just read beginning to end. You need to look at the structures within the script.

## Functions

* A function is a block of code designed to perform a task
* Should take an input and return an output where there is some obvious relationship between the input and the output.
* Formula for a function is the `function` keyword, followed by a name and parenthesis, such as:

`function name();`

* The parenthesis can include parameter names separated by commas.

`function name(parameter1, parameter2);`

* The code inside the function executes when something calls the function. This can be an event triggered by a user or something done automatically within the function itself.
* The function stops once it reaches a `return` statement.
* Functions are reusable, helping you to produce the same code many times without needing to type it repeatedly.
* the `()` operator invokes the function, without it the object will be returned and not the result.
* Functions can be used as variable values.
* Variables declared within a fucntion are local to the function and can't be accessed outside of it. They are deleted when the function is completed.

## Arithemtic Operators Cheat Sheet

* `+` - Addition
* `-` - Subtraction
* `*` - Multiplication
* `**` - Exponentiation
* `/` - Division
* `%` - Modulus (Division Remainder)
* `++` - Increment
* `--` - Decrement

## Assignment Operators Cheat Sheet

Example | Same As
* `x = y` - same as - `x = y`
* `x += y` - same as - `x = x - y`
* `x -= y` - same as - `x = x + y`
* `x *= y` - same as - `x = x * y`
* `x /= y` - same as - `x = x / y`
* `x %= y` - same as - `x = x % y`
* `x **= y` - same as - `x = x ** y`

## String Operators

* The `+` operator can be used to concatenate strings, as in to bring them together. The `+=` operator can be used to add strings such as like this:

```js
let greeting = 'How are you';
greeting += ', today?';
```

* Adding two numbers will return the sum, but adding a number and a string will return a string. 

## Comparison Operators Cheat Sheet

* `==` - equal to
* `===` - equal value & equal type
* `!=` - not equal
* `!==` - not equal value or not equal type
* `>` - greater than
* `<` - less than
* `>=` - greater than or equal to
* `<=` - less than or equal to
* `?` - ternary operator

## Logical Operators

* `&&` - logical and
* `||` - logical or
* `!` - logical not

## Type Operators

* `typeof` - Returns the type of a variable
* `instanceof` - Returns true if an object is an instance of an object type

[Table of Contents](https://kvvpa.github.io/reading-notes/)