# Notes for Read 07

## Control Flow

*the control flow is the order in which the computer executes statements in a script. Code is run in order from the first line in the file to the last line, unless the computer runs across structures that change the control flow, such as conditional and loops. Control flow means that when you read a script, you must not only read from start to finish but also look at program structure and how it affects order of execution.*

## JavaScript Functions

*A JavaScript funtion is a block of code designed to perform a particular task. It is executed when "something" invokes it (calls it).*

     **Example**

  funtion myFunction(p1, p2) {
    return p1 * p2;  // The funtion returns the product of p1 and p2
  }

## JavaScript Function Syntax

 *A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside curly brackets: {}*

    **example**

function name(parameter1, parameter2, parameter3) {
  // code to be executed
}

Function parameters are listed inside the parentheses () in the function definition.

Function arguments are the values received by the function when it is invoked.

Inside the function, the arguments (the parameters) behave as local variables.

## Function Invocation

The code inside the function will execute when "something" invokes (calls) the function:

When an event occurs (when a user clicks a button)
When it is invoked (called) from JavaScript code
Automatically (self invoked)

## Function Return

When JavaScript reaches a return statement, the function will stop executing.

If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

Functions often compute a return value. The return value is "returned" back to the "caller":

    **Example**
Calculate the product of two numbers, and return the result:

let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}
The result in x will be: 12

## Why Functions

You can reuse code: Define the code once, and use it many times.

You can use the same code many times with different arguments, to produce different results.

    **Example**

Convert Fahrenheit to Celsius:

function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius(77);

The () Operator Invokes the Function
Using the example above, toCelsius refers to the function object, and toCelsius() refers to the function result.

Accessing a function without () will return the function object instead of the function result.

## JavaScript Arithmetic Operators

The assignment operator (=) assigns a value to a variable.

The addition operator (+) adds numbers:

The multiplication operator (*) multiplies numbers.

Arithmetic operators are used to perform arithmetic on numbers:

 Operator Description
    +Addition
    - Subtraction
    * Multiplication
    ** Exponentiation (ES2016)
    / Division
    % Modulus (Division Remainder)
    ++ Increment
    -- Decrement
