# Shakil
Test Environment for Advanced Projects

//JS ECMA

function Shakil (){

}

Math.random()		//This method returns a random number between 0 and 1. This code prints a random number between 0 and 1.

Math.floor()		//rounds the number down to the nearest whole number.

console.log(Math.floor(Math.random() * 100));

console.log(Math.ceil(43.8));

console.log(Number.isInteger(2017));

That's where variables come in. 
Variables allow us to assign data to a word and use the word to reference the data. 
If the data changes (like degrees Celsius) we can replace the variable's value instead of re-writing the program.

const, is short for constant which is a constant variable in javascript.

myName is the variable's name. 
Notice that the word has no spaces, and we capitalized the N. 
Capitalizing in this way is a standard convention in JavaScript called camelCasing, because the capital letters look like the humps on a camel's back.

The JavaScript term for inserting the data saved to a variable into a string is string interpolation.

The + operator, known until now as the addition operator, is used to interpolate (insert) a string variable into a string, as follows:

Backticks are amazing

the + operator is used to interpolate (combine) multiple strings.

In JavaScript ES6, backticks (`) and ${} are used to interpolate values into a string.

The core task of programming is writing lists of instructions for computers, or translating our ideas from human-speak to computer-speak.


if/else statements are how programs can process yes/no questions programmatically.

All variables that have been declared and assigned are truthy unless they contain one of the six values listed below:

false
0 and -0
"" and '' (empty strings)
null
undefined
NaN (Not a Number)





let favoritePhrase = '';

if (favoritePhrase) {
  console.log("This string doesn't seem to be empty.");
} else {
  console.log('This string is definitely empty.');
}


There are two comparisons you might be familiar with:

Less than: <
Greater than: >
You may also recognize these:

Less than or equal to: <=
Greater than or equal to: >=
These comparisons evaluate to true or false.



In English, sometimes we say "both of these things" or "either one of these things." Let's translate those phrases into JavaScript with special operators called logical operators.

To say "both must be true," we use &&.
To say "either can be true," we use ||.




Using else if is a great tool for when we have a few different conditions we'd like to consider.

else if is limited, however. If we want to write a program with 25 different conditions, like a JavaScript cash register, we'd have to write a lot of code, and it can be difficult to read and understand.

To deal with times when you need many else if conditions, we can turn to a switch statement to write more concise and readable code.

To a computer, a switch statement and an if/else statement are the same, but a switch statement can be easier for other humans to read. Part of being a good developer is writing code that both computers and other humans can read.







Way to go! We just learned a lot of control flow concepts:

if/else statements make binary decisions and execute different code based on conditions.
All conditions are evaluated to be truthy or falsy.
We can add more conditional statements to if/else statements with else if.
switch statements make complicated if/else statements easier to read and achieve the same result.
The ternary operator (?) and a colon (:) allow us to refactor simple if/else statements.
Comparison operators, including <, >, <=, and >= can compare two variables or values.
After two values are compared, the conditional statement evaluates to true or false.
The logical operator && checks if both sides of a condition are truthy.
The logical operator || checks if either side is truthy.
The logical operator !== checks if the two sides are not equal.
An exclamation mark (!) switches the truthiness / falsiness of the value of a variable.
One equals symbol (=) is used to assign a value to a variable.
Three equals symbols (===) are used to check if two variables are equal to each other.


