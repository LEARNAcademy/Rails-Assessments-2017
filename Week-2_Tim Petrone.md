### Rails Course Assessment

## Week 2 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Describe what "if" does in Javascript.
  Ifs are used primarily in functions. They are commands that will do certain actions depending on certain criteria. These can be broken out to 2 or more actions.

#### 2. What is a closure, and what is it used for?
[Your Answer]
  Closures are function inside of functions that both use return to grab parent variables and change them and output an answer that will not brake the parent code.

[Googled Answer]
Closures are useful because they let you associate some data (the lexical environment) with a function that operates on that data. This has obvious parallels to object oriented programming, where objects allow us to associate some data (the object's properties) with one or more methods.

#### 3. Write a function that takes one number as a parameter and decides if that number is divisible by three or not. If it is, print the number and "is divisible by three". If it is not, print that the number "is not divisible by three".
function divByThree(x) {
  var remainder = x % 3;
  if (remainder == 0){
    return x + " is divisible by three."
  } else {
    return x + " is not divisible by three."
  }
}

#### 4. What is JSON?
//Your Answer


//Googled Answer
JSON (JavaScript Object Notation) is a lightweight data-interchange format. It is easy for humans to read and write. It is easy for machines to parse and generate.

#### 5. Write about yourself in an object, giving at least three properties of you. Then store your object in a variable with your name.
var Tim = {firstName: "Timothy", lastName: "Petrone", age: 26, middleInitial: "M", eyes: "brown"}

#### 6. Explain what an "event" is (within the context of a webpage).

//Your Answer
An event is the action a user takes on the page, whether it be a click or otherwise.

//Googled Answer


#### 7. What's the difference between =, ==, and === in JavaScript?
//Your Answer
One equal sign sets a value to a variable. Two equal signs check if the 2 elements are the same, but loosely. Three equal signs check if the 2 elements are exactly the same.

//Googled Answer
In computer programming, event-driven programming is a programming paradigm in which the flow of the program is determined by events such as user actions (mouse clicks, key presses), sensor outputs, or messages from other programs/threads.

#### 8. Given the array below, create two console.logs that print the 2nd and 5th elements respectively. Try to access the values using a different syntax each time.

```js

var newArray = [1, "4", "echo", true, "green"]
console.log(newArray[1]);
console.log(newArray.pop())
```

#### 9. List the different kinds of javascript loops and describe what they do.
//Your Answer
for loop - loops through a series of actions until a certain criteria is met.
forEach loop - loops through a series of actions for every element given.
while loop - similar to for loops, but the actions execute before the criteria is read.
for if loops - loops through a series of actions for every element if it meets a certain criteria.

//Googled Answer
for - loops through a block of code a number of times.
for/in - loops through the properties of an object.
while - loops through a block of code while a specified condition is true.
do/while - also loops through a block of code while a specified condition is true.

#### 10. How would you explain "scope" in javascript?
//Your Answer
Scope is the container that the element is in. Global scope is if a variable is defined outside all functions, so it is at the base/top layer. Within functions are local variables. The function is the local scope and everything in the base layer is global. the function can grab other elements from the global variable but not vice versa. If a function is defined within a function, it is a nested function, making the original function a higher order function. The nested function now has its own local variable and can grab from the higher function or even the global scope.

//Googled Answer
Scope is the accessibility of variables, functions, and objects in some particular part of your code during runtime. In other words, scope determines the visibility of variables and other resources in areas of your code.
