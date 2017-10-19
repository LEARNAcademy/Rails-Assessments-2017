Rails Course Assessment

Week 2 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

1. Describe what "if" does in Javascript.

An "if" statement lists a set of actions in curly-brackets that are triggered if certain conditions are met. They can simply have one set of actions triggered by one condition, but also conditions that that are checked sequentially to trigger additional actions as the previous conditions are not met ("else-if"), and/or a final set of actions that are triggered if no set of listed conditions are met ("else").

2. What is a closure, and what is it used for?

A closure is when a function returns a nested (often anonymous) function that access or changes a variable above its scope. This is often used for counters or other uses that involve changing a variable by a set amount every time the function runs. Closures can be useful to allow functions to keep track of how many times something occurs while reducing the unnecessary use of global variables.

[Googled Answer]

A closure is an inner function that has access to the outer (enclosing) function’s variables—scope chain. The closure has three scope chains: it has access to its own scope (variables defined between its curly brackets), it has access to the outer function’s variables, and it has access to the global variables. The inner function has access not only to the outer function’s variables, but also to the outer function’s parameters. Note that the inner function cannot call the outer function’s arguments object, however, even though it can call the outer function’s parameters directly. You create a closure by adding a function inside another function.

3. Write a function that takes one number as a parameter and decides if that number is divisible by three or not. If it is, print the number and "is divisible by three". If it is not, print that the number "is not divisible by three".

function isDivisibleByThree(dividend){
  var answer;
  if (dividend % 3 == 0){
    answer = dividend + " is divisible by three";
  } else {
    answer = dividend + " is not divisible by three";
  }
  return answer;
}

4. What is JSON?

//Your Answer
A syntax for defining/listing objects and their properties, listing each key paired with its value.
//Googled Answer
JSON (JavaScript Object Notation) is a lightweight data-interchange format. It is easy for humans to read and write. It is easy for machines to parse and generate. It is based on a subset of the JavaScript Programming Language, Standard ECMA-262 3rd Edition - December 1999. JSON is a text format that is completely language independent but uses conventions that are familiar to programmers of the C-family of languages, including C, C++, C#, Java, JavaScript, Perl, Python, and many others. These properties make JSON an ideal data-interchange language.

5. Write about yourself in an object, giving at least three properties of you. Then store your object in a variable with your name.
var andrewLevy = {name: "Andrew Levy", isVeryCool: true, dislikes: ["closures", "unexpected identifier errors"]};

6. Explain what an "event" is (within the context of a webpage).

Something that happens, often triggered by a user interaction, after a page has loaded which causes a script or portion of a script to run.

//Googled Answer

HTML events are "things" that happen to HTML elements. When JavaScript is used in HTML pages, JavaScript can "react" on these events.

7. What's the difference between =, ==, and === in JavaScript?

//Your Answer

= is used to define things such as objects, variables and arrays.
== checks whether two things are equivalent.
=== checks whether two things are exactly the same.

== is less strict than ===. For instance: 1 === "1" returns false, while 1 == "1" returns true.

//Googled Answer
The choice of which operation to use depends on what sort of comparison you are looking to perform. Briefly, double equals will perform a type conversion when comparing two things; triple equals will do the same comparison without type conversion (by simply always returning false if the types differ); and Object.is will behave the same way as triple equals, but with special handling for NaN and -0 and +0 so that the last two are not said to be the same, while Object.is(NaN, NaN) will be true.

8. Given the array below, create two console.logs that print the 2nd and 5th elements respectively. Try to access the values using a different syntax each time.

var newArray = [1, "4", "echo", true, "green"]

console.log(newArray[1], newArray.splice(4).join(""));
console.log(newArray.slice(1, 2).join(""), newArray.pop());

9. List the different kinds of javascript loops and describe what they do.

//Your Answer
"While" loops run a set of actions as long as the set conditions are true.
"Do while" loops run their actions once, and then continue to run them as long as the set conditions are true.
"For" loops have a set end condition and an iterator to change/test after every run to check and see if the end condition has been met.
"For each" loops are similar to "for" loops but are meant for arrays and run once for each element in the array.

//Googled Answer

For Loops: When you know how many times you want to loop. When you are iterating through the indices of an array. When you have some sort of counter.
For-In Loops: When you are iterating over the properties of an object.
For-Each: When you want to iterate over the values of an object's properties.
While Loops: When you may be unsure of the number of times to loop. When you want to loop while some condition is true.
Do-While Loops: When you want it to loop at least once before checking if the condition is true.

10. How would you explain "scope" in javascript?

//Your Answer

When code is running in a set of curly-brackets (the current scope), it only has access to variables, functions etc. that are in the same set of brackets or within brackets that contain the current set of brackets. All scopes have access to scopes above them (including global variables), but not different sets of brackets on the same level, or lower scopes (you can't access a variable defined inside a loop or function that is not currently running, for instance).

//Googled Answer

In JavaScript there are two types of scope:
Local scope
Global scope
JavaScript has function scope: Each function creates a new scope. Scope determines the accessibility (visibility) of these variables. Variables defined inside a function are not accessible (visible) from outside the function.
