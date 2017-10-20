### Rails Course Assessment

## Week 2 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Describe what "if" does in Javascript.

The if is a conditional statement. If the condition is true, it executes the code. You can use it on its own, with else if, or else.

#### 2. What is a closure, and what is it used for?

[Your Answer] A closure is a function that returns another function. It helps with scoping since the inner function can see the variables of their parent function.

[Googled Answer] A closure is the combination of a function and the lexical environment within which that function was declared.

In other words, a closure gives you access to an outer function’s scope from an inner function. In JavaScript, closures are created every time a function is created, at function creation time. To use a closure, simply define a function inside another function and expose it. To expose a function, return it or pass it to another function. Among other things, closures are commonly used to give objects data privacy.

#### 3. Write a function that takes one number as a parameter and decides if that number is divisible by three or not. If it is, print the number and "is divisible by three". If it is not, print that the number "is not divisible by three".

```js
function isDivByThree(x){
  if (x % 3 == 0){
    console.log(x + " is divisible by three");
  }
  else {
    console.log(x + " is not divisible by three");
  }
}

```

#### 4. What is JSON?

//Your Answer: JSON is JavaScript Object Notation.

//Googled Answer: JSON (JavaScript Object Notation) is a lightweight data-interchange format. It is easy for humans to read and write. It is easy for machines to parse and generate. When exchanging data between a browser and a server, the data can only be text. JSON is text, and we can convert any JavaScript object into JSON, and send JSON to the server. We can also convert any JSON received from the server into JavaScript objects. This way we can work with the data as JavaScript objects, with no complicated parsing and translations.

#### 5. Write about yourself in an object, giving at least three properties of you. Then store your object in a variable with your name.

```js
var Cris = {
  eyesColor: "blue",
  hairColor: "blond",
  height: 1,76,
  isLearning: true  
}
```

#### 6. Explain what an "event" is (within the context of a webpage).

//Your Answer: Events are things that happen on the site. (I'm not so sure about this concept).

//Googled Answer: HTML events are "things" that happen to HTML elements. When JavaScript is used in HTML pages, JavaScript can "react" on these events. An HTML event can be something the browser does, or something a user does. Examples: an HTML web page has finished loading, an HTML input field was changed, an HTML button was clicked. Often, when events happen, you may want to do something. JavaScript lets you execute code when events are detected.

#### 7. What's the difference between =, ==, and === in JavaScript?

//Your Answer: = assigns a value. == compares if the value is equal to another value. ===  compares if the value is equal to another value and if they are the same data type.

//Googled Answer: Assignment operators are used to assign values to JavaScript variables (=). Comparison operators are used in logical statements to determine equality or difference between variables or values (==	equal to, ===	equal value and equal type).

#### 8. Given the array below, create two console.logs that print the 2nd and 5th elements respectively. Try to access the values using a different syntax each time.

```js

var newArray = [1, "4", "echo", true, "green"]

console.log(newArray[1]);
console.log(newArray[newArray.length-1]);

```

#### 9. List the different kinds of JavaScript loops and describe what they do.

//Your Answer: The for loop takes a condition as the starting point, the ending point and the increment pattern. It'll loop using these conditions and execute the code. A while loop will execute code while a condition is met. If the condition is never met, it will never execute. A do while loop will always execute at least once and then check if the condition is met to see if it runs again. A forEach loop and a for in loop are both performed on arrays. They will loop through each item of the array and execute the code, but have different syntax.

//Googled Answer: Loops can execute a block of code a number of times. JavaScript supports different kinds of loops:
for - loops through a block of code a number of times
for/in - loops through the properties of an object
while - loops through a block of code while a specified condition is true
do/while - will execute the code block once, before checking if the condition is true, then it will repeat the loop as long as the condition is true.

#### 10. How would you explain "scope" in JavaScript?

//Your Answer: It refers to where a variable can be seen and used in the code. There is global scope and local scope. Putting variables in global scope will make them accessible by all. Local variables can only be used within a block so they are more secure. Local scope can see everything, but global scope can't see local scope.

//Googled Answer: Scope determines the accessibility (visibility) of variables. In JavaScript there are two types of scope: Local scope and Global scope. JavaScript has function scope: Each function creates a new scope.
Variables defined inside a function are not accessible (visible) from outside the function.
