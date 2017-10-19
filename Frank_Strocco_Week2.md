sd### Rails Course Assessment

## Week 2 Assessment
Í
Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Describe what "if" does in Javascript.

if is a conditional operation with a block. If the if passes it will run whatever you
code you put in the block. you can add else or else if's as well for multiple mixtures of conditions.

#### 2. What is a closure, and what is it used for?

[Your Answer]

a closure is a function inside another function that relies on the outside function's variable
to work. I know that from memory. :P  It basically can change a variable and keep and return that variable when it wants, without it being reset outside that function where the variable was defined.

You can use if for counters or for storing sensitive information. Many more things as well, i'm sure.
-----------

[Googled Answer]

Closures are one of the most powerful features of JavaScript. JavaScript allows for the nesting of functions and grants the inner function full access to all the variables and functions defined inside the outer function (and all other variables and functions that the outer function has access to)

you could use it to run private functions

#### 3. Write a function that takes one number as a parameter and decides if that number is divisble by three or not. If it is, print the number and "is divisible by three". If it is not, print that the number "is not divisble by three".

function oneNum(num){
  return num % 3 == 0 ? true : false;
}

oneNum(3); // => true
oneNum(2); // => false

#### 4. What is JSON?

//Your Answer

can't remember :(
----------


//Googled Answer

JSON (JavaScript Object Notation) is a lightweight data-interchange format. It is easy for humans to read and write. It is easy for machines to parse and generate. It is based on a subset of the JavaScript Programming Language, Standard ECMA-262 3rd Edition - December 1999. JSON is a text format that is completely language independent but uses conventions that are familiar to programmers of the C-family of languages, including C, C++, C#, Java, JavaScript, Perl, Python, and many others. These properties make JSON an ideal data-interchange language.
---------

#### 5. Write about yourself in an object, giving at least three properties of you. Then store your object in a variable with your name.

MySelf = {
  height: "6ft tall",
  weight: "185 pounds",
  hair: "out of control"
}
Frank = MySelf;



#### 6. Explain what an "event" is (within the context of a webpage).

//Your Answer
An event is when the browser is listening for something to happen. Could be a page load
could be mouse over (hover), a click.. ect It can trigger js and jquery to run.
--------------

//Googled Answer

HTML DOM events allow JavaScript to register different event handlers on elements in an HTML document.

Events are normally used in combination with functions, and the function will not be executed before the event occurs (such as when a user clicks a button).
--------
#### 7. What's the difference between =, ==, and === in JavaScript?

//Your Answer
single = is an assignment
double == is a comparison
tripple === is a strong comparison on the object level
 ----------

//Googled Answer

Comparison operators. JavaScript has both strict and type–converting comparisons. A strict comparison (e.g., === ) is only true if the operands are of the same type and the contents match. The more commonly-used abstract comparison (e.g. == ) converts the operands to the same type before making the comparison.
------------

#### 8. Given the array below, create two console.logs that print the 2nd and 5th elements respectively. Try to access the values using a different syntax each time.

```js

var newArray = [1, "4", "echo", true, "green"]
console.log(newArray[1]);
console.log(newArray.pop());
console.log(newArray.slice(4));
```

#### 9. List the different kinds of javascript loops and describe what they do.

//Your Answer
while loop. runs while a condition is true
for loop. . runs till a set variable condition is incremented and a condition is still true
forEach ..  runs each element an array or hash(object)
---------
//Googled Answer

for - loops through a block of code a number of times.
for/in - loops through the properties of an object.
while - loops through a block of code while a specified condition is true.
do/while - also loops through a block of code while a specified condition is true.

--------------

#### 10. How would you explain "scope" in javascript?

//Your Answer
scope is how you set your variables and where you use them..
var myVar = 6; declared outside a function is a global variable. It works inside and outside functions
let myVar = 3; is the smallest scope variable. it works only in a block (lexical scope) maybe :p
const MYCONSTANT = 1; is constant variable and works anywhere.

//Googled Answer

JavaScript has two scopes – global and local. Any variable declared outside of a function belongs to the global scope, and is therefore accessible from anywhere in your code. Each function has its own scope, and any variable declared within that function is only accessible from that function and any nested functions.
