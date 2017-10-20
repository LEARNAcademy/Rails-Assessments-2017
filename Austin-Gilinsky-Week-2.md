### Rails Course Assessment

## Week 2 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Describe what "if" does in Javascript.
It will execute a code in a condition is met.

#### 2. What is a closure, and what is it used for?


[Your Answer]


A closure is an inner function that has access to the outer (enclosing) function’s variables—scope chain. The closure has three scope chains: it has access to its own scope (variables defined between its curly brackets), it has access to the outer function’s variables, and it has access to the global variables.


#### 3. Write a function that takes one number as a parameter and decides if that number is divisble by three or not. If it is, print the number and "is divisible by three". If it is not, print that the number "is not divisble by three".

var x = 9;
  if (x % 3 == 0) {
    console.log(x + " is divisible by three");
  } else {
    console.log(x + " is not divisible by three");
   }
}


#### 4. What is JSON?

//Your Answer

The JavaScript Object Notation (JSON) is a data-interchange format.  Although not a strict subset, JSON closely resembles a subset of JavaScript syntax. Though many programming languages support JSON, JSON is especially useful for JavaScript-based apps, including websites and browser extensions.

#### 5. Write about yourself in an object, giving at least three properties of you. Then store your object in a variable with your name.

let person = {
  firstName: Austin
  lastName: Gilinsky
  age: 29
  height: 5'10"
};


#### 6. Explain what an "event" is (within the context of a webpage).

//Event is when something happens on the webpage. Like a click on a button.

//Googled Answer

#### 7. What's the difference between =, ==, and === in JavaScript?

= assigns values to something
== means something is true
=== means something is false

//Googled Answer


#### 8. Given the array below, create two console.logs that print the 2nd and 5th elements respectively. Try to access the values using a different syntax each time.

```js

var newArray = [1, "4", "echo", true, "green"]
console.log(newArray[1],[4]);

```

#### 9. List the different kinds of javascript loops and describe what they do.

for loops repeat until a specified condition is met
while loops will keep going as long as the condition is true and will stop when it is false.

while loops- zero or many loops
do while loops- one or many loops


#### 10. How would you explain "scope" in javascript?
scope can be global or local. local can see global but global cannot see local.
local scope: variable is set inside a function.
global scope: varibale is set outside function.


In the JavaScript language there are two types of scopes:

Global Scope
Local Scope
Variables defined inside a function are in local scope while variables defined outside of a function are in the global scope. Each function when invoked creates a new scope.
