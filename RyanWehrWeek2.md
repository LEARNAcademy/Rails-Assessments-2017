### Rails Course Assessment

## Week 2 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Describe what "if" does in Javascript.

Its comparing one thing to another. Like a check.


#### 2. What is a closure, and what is it used for?


A closure holds onto local variables instead of clearing them.


A closure is a persistent scope which holds on to local variables even after the code execution has moved out of that block. Languages which support closure (such as JavaScript, Swift and Ruby) will allow you to keep a reference to a scope (including its parent scopes), even after the block in which those variables were declared has finished executing, provided you keep a reference to that block or function somewhere.


#### 3. Write a function that takes one number as a parameter and decides if that number is divisble by three or not. If it is, print the number and "is divisible by three". If it is not, print that the number "is not divisble by three".

function(x) {
  if x % 3 == 0 {
    console.log(x + "is divisible by 3!")
  } else {
    console.log(x + " is NOT divisible by 3!")
  }
}


#### 4. What is JSON?

JSON is a file storage type.

In computing, JavaScript Object Notation or JSON, is an open-standard file format that uses human-readable text to transmit data objects consisting of attribute–value pairs and array data types.

#### 5. Write about yourself in an object, giving at least three properties of you. Then store your object in a variable with your name.

var ryan = {age:18, gender:"Male", favColor:"Red"};

#### 6. Explain what an "event" is (within the context of a webpage).

Events are actions that can be listened for to execute other things.
Like clicking a button. (user interactions.)

In programming, an event is an action that occurs as a result of the user or another source, such as a mouse being clicked, or a key being pressed. An event handler is a routine that is used to deal with the event, allowing a programmer to write code that will be executed when the event occurs.

#### 7. What's the difference between =, ==, and === in JavaScript?

=; Setting something
==; Comparing two things (not strict)
===; Comparing things (strict)

=== and !== are strict comparison operators: JavaScript has both strict and type-converting equality comparison. ... Positive and negative zeros are equal to one another. Two Boolean operands are strictly equal if both are true or both are false.


#### 8. Given the array below, create two console.logs that print the 2nd and 5th elements respectively. Try to access the values using a different syntax each time.

```js

var newArray = [1, "4", "echo", true, "green"]
var index2 = newArray[2]

console.log(index2)
console.log(newArray[5])
```

#### 9. List the different kinds of javascript loops and describe what they do.

for - like foreach(i think?) Older better to use foreach.

foreach - Runs through each task that is specified

while - Runs until a certain set of parameters are met.

In computer science, a for-loop (or simply for loop) is a control flow statement for specifying iteration, which allows code to be executed repeatedly.

The while Loop. ... The purpose of a while loop is to execute a statement or code block repeatedly as long as an expression is true. Once the expression becomes false, the loop terminates


#### 10. How would you explain "scope" in javascript?

Scope is the determining factor of how or where you can use some variables. Global vars are accessible from everywhere as local vars cant be accessed globally.

JavaScript has two scopes – global and local. Any variable declared outside of a function belongs to the global scope, and is therefore accessible from anywhere in your code. Each function has its own scope, and any variable declared within that function is only accessible from that function and any nested functions.
