### Rails Course Assessment

## Week 2 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Describe what "if" does in Javascript.
if is a conditional statement. It evaluates a statement, and if that statement is true, it will then execute a block of code. If the statement is not true, it won't execute anything.

#### 2. What is a closure, and what is it used for?
[Your Answer]
Closures are a way to return values from within embedded functions to be used and saved globally as part of 'higher order functions'.

[Googled Answer]
"A closure is an inner function that has access to the outer (enclosing) function's variables—scope chain. The closure has three scope chains: it has access to its own scope (variables defined between its curly brackets), it has access to the outer function's variables, and it has access to the global variables."

#### 3. Write a function that takes one number as a parameter and decides if that number is divisble by three or not. If it is, print the number and "is divisible by three". If it is not, print that the number "is not divisble by three".
function divisbleByThree (number) {
  if (number % 3 == 0) {
    console.log(number + " is divisble by three");
  }else{
    console.log(number + " is not divisible by three");
  };
};

#### 4. What is JSON?
//Your Answer
JSON is the syntax for which JavaScript objects are written in.

//Googled Answer
"JSON (JavaScript Object Notation) is a lightweight data-interchange format. It is easy for humans to read and write. It is easy for machines to parse and generate. It is based on a subset of the JavaScript Programming Language."

#### 5. Write about yourself in an object, giving at least three properties of you. Then store your object in a variable with your name.
var Kiah = {name: "Kiah", age: "19", fav_number: "9" }

#### 6. Explain what an "event" is (within the context of a webpage).
//Your Answer
An "event" is when an event that happens within the webpage triggers an action, such as an on-click event.

//Googled Answer
"JavaScript's interaction with HTML is handled through events that occur when the user or the browser manipulates a page... every HTML element contains a set of events which can trigger JavaScript Code."

#### 7. What's the difference between =, ==, and === in JavaScript?
//Your Answer
The single = is used when setting a variable equal to some value. The double == is used when comparing two values to see if they are the same. The triple === is used when comparing two values and their data types to determine if they are exactly the same.

//Googled Answer
The = is an assignment operator and the == and === are relational operators, === being more specific.

#### 8. Given the array below, create two console.logs that print the 2nd and 5th elements respectively. Try to access the values using a different syntax each time.

```js

var newArray = [1, "4", "echo", true, "green"]
console.log(newArray[1]);
console.log($(newArray).last());
```

#### 9. List the different kinds of javascript loops and describe what they do.
//Your Answer
A while loop is is similar to an if statement in that as long as a particular statement is true (usually a counter set to a specific number of iterations), it will execute its code.
a do while loop is the same as a while loop, except that its code will always execute at least once before determining its conditional.
A for loop is similar to a while loop in that one can specify the number of iterations they want it to loop through, but a for loop is particularly useful on arrays.
A forEach loop is a type of loop that will iterate for as many elements that are in an array.

//Googled Answer
"The while loop loops through a block of code as long as a specified condition is true."
"The do/while loop will execute the code block once, before checking if the condition is true, then it will repeat the loop as long as the condition is true."
"A for loop loops through a block of code a number of times"
"The forEach() method executes a provided function once for each array element."

#### 10. How would you explain "scope" in javascript?
//Your Answer
Scope refers to which parts of a program can "see" the elements/values/variables in other parts (or blocks) of the program. Nested blocks can access all of the variables up the scope, or in broader blocks, all the way up to the global scope. But a program can not use variables from any of the narrower levels down the scope.

//Googled Answer
"Scope determines the accessibility (visibility) of variables. Variables defined inside a function are not accessible (visible) from outside the function."
