### Rails Course Assessment

## Week 2 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Describe what "if" does in Javascript.
The "if" sets a condition for the program to check for, and if that condition is met, the result of the if will run.


#### 2. What is a closure, and what is it used for?


[Your Answer]
A closure is a function within a function. They are used for many things! One thing is that they can be used in objects; values can be functions. So, when you access that value, the function runs.

[Googled Answer]

A closure is an inner function that has access to the outer (enclosing) function's variables—scope chain. The closure has three scope chains: it has access to its own scope (variables defined between its curly brackets), it has access to the outer function's variables, and it has access to the global variables.


#### 3. Write a function that takes one number as a parameter and decides if that number is divisble by three or not. If it is, print the number and "is divisible by three". If it is not, print that the number "is not divisble by three".

function isDivisible(x) {
  if (x % 3 == 0) {
    console.log(x + "is divisible by three")
  } else {
    console.log(x + "is not divisible by three")
  }
};

#### 4. What is JSON?

//Your Answer

I'm not sure exactly. I've looked at a few resources and I still don't quite understand. From what I gather, it is a way of writing objects that is easier to read.

//Googled Answer
JSON (JavaScript Object Notation) is a lightweight data-interchange format. It is easy for humans to read and write. It is easy for machines to parse and generate.

#### 5. Write about yourself in an object, giving at least three properties of you. Then store your object in a variable with your name.

var veronica {
  name: "Veronica",
  hairColor: "brown",
  height: "5'5"
}


#### 6. Explain what an "event" is (within the context of a webpage).

//Your Answer

An event is when you do something on a web page to make it change. For example, if you click a button and something happens, like the button changes colors, that is an event.

//Googled Answer

Each available event has an event handler, which is block of code (usually a user-defined JavaScript function) that will be run when the event fires. When such a block of code is defined to be run in response to an event firing, we say we are registering an event handler

#### 7. What's the difference between =, ==, and === in JavaScript?

//Your Answer

The first, =, sets a variable to a value. The second, ==, roughly means "is similar to". The third, ===, means that one thing is exactly equal to another.

//Googled Answer

By using = you assign a value to something.

x = 1 //x now equals 1

By using == you check if something is equal to something else. This is not strict

x == 1 //is x equal to 1? (False)
true == 1 //does the boolean value of true equal 1? (True)

By using === you check if something is equal to something else. This is also strict.


#### 8. Given the array below, create two console.logs that print the 2nd and 5th elements respectively. Try to access the values using a different syntax each time.

```js

var newArray = [1, "4", "echo", true, "green"]

```
console.log(newArray[1, 4]);
console.log(newArray.length-1, newArray.length -4)

#### 9. List the different kinds of javascript loops and describe what they do.

//Your Answer
while: while a certain condition exists, do the outcome.
for: for each element in iteration that is specified, up to a certain number of iterations, do the outcome.
forEach: for each element in an array, do the outcome.
forIn

//Googled Answer

for - loops through a block of code a number of times.
for/in - loops through the properties of an object.
while - loops through a block of code while a specified condition is true.
do/while - also loops through a block of code while a specified condition is true.


#### 10. How would you explain "scope" in javascript?

//Your Answer

There is global scope and local scope. This tells how a variable is accessed; if it is local, it can be accessed only locally, such as within its function. But, if it is global, it is accessible anywhere in the code.

//Googled Answer

Scope refers to the visibility of variables. In other words, which parts of your program can see or use it. Normally, every variable has a global scope. Once defined, every part of your program can access a variable. It is very useful to be able to limit a variable's scope to a single function.
