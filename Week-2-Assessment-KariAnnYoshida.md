Rails Course Assessment

Week 2 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

1. Describe what "if" does in Javascript.
An "if" statement is used to put conditions on having something done. ie. "do this thing, 'if' these conditions are met."

2. What is a closure, and what is it used for?

[Your Answer]
A closure is a when a function returns a function. This avoids the problem of having global variables.

[Googled Answer]
A closure is the combination of a function and the lexical environment in which that function was declared. Closures take into account the scope of a function, inner functions are able to access the variables defined outside of its function but cannot access those declared within.

3. Write a function that takes one number as a parameter and decides if that number is divisble by three or not. If it is, print the number and "is divisible by three". If it is not, print that the number "is not divisble by three".

function isMultThree(num){
  if (num % 3 == 0){
    console.log(num);
  }else {
  console.log("is not divisible by three")
  }
}

4. What is JSON?

//Your Answer
i actually don't remember...
//Googled Answer
JSON is a format for storing and transporting data.
JSON is often used when data is sent from a server to a web page.
JSON stands for JavaScript Object Notation. It can create objects with the same syntax as javascript.
{
"employees":[
    {"firstName":"John", "lastName":"Doe"},
    {"firstName":"Anna", "lastName":"Smith"},
    {"firstName":"Peter", "lastName":"Jones"}
]
}

5. Write about yourself in an object, giving at least three properties of you. Then store your object in a variable with your name.

var KariAnn = {
height: "4ft 10in",
age: 23,
ethnicity: Japanese
}

6. Explain what an "event" is (within the context of a webpage).

//Your Answer
An event is an instance of some interactive thing happenning. for example, clicking a button or a position on the screen could be considered an "event" which could be connected to run a function (ie an on."click").

//Googled Answer
HTML events are "things" that happen to HTML elements.
When JavaScript is used in HTML pages, JavaScript can "react" on these events.
An HTML event can be something the browser does, or something a user does.
Here are some examples of HTML events:
An HTML web page has finished loading
An HTML input field was changed
An HTML button was clicked
Often, when events happen, you may want to do something.
JavaScript lets you execute code when events are detected.
HTML allows event handler attributes, with JavaScript code, to be added to HTML elements.

7. What's the difference between =, ==, and === in JavaScript?

//Your Answer
the '=' is used when assigning a value to a variable. If you have  'a = 3', you are saying that the value of a will be 3.
the '==' is used when saying that the value of one thing should be equal to something else. for example: the boolean true == 1 will be considered true. The value of true does equal to 1 even though the way that it is written is not EXACT.
the '===' is used to show that something is EXACTLY the same as something else. So the above example (true === 1) would actually be FALSE. because true is a boolean and 1 is a number so they are not EXACTLY the same, even though the above would be true. the === is more strict than the ==.

//Googled Answer

8. Given the array below, create two console.logs that print the 2nd and 5th elements respectively. Try to access the values using a different syntax each time.

var newArray = [1, "4", "echo", true, "green"]

console.log(newArray[1,4])

console.log

9. List the different kinds of javascript loops and describe what they do.

//Your Answer
"for" Loops: Will execute a block of code if certain criteria are met. For the criteria you can set it to iterate through the loop by setting a variable (i=0; i<5; i++). So this means that the variable i will be initially set to 0, and while i is less than 5 it will execute the code, and each time the code is executed the variable i will increase by 1 so that it will iterate the specified number of times and then stop. "for" loops are usually used for arrays.

"while": While loops are similar, in that while certain conditions are met the following block of code will run. So while (i<10) for example it might run a certain block of code, and then at the end of that block it will increase the count of i (i++) that way it will keep running through the loop until the value of i is greater than 10. While loops are a 0 or many loop, where it will either run 0 times if the conditions are not met, or it will run many times until it no longer meets the criteria to run.

"do/while": Do/while loops are similar to while loops. In the "do" portion it will have a block of code to execute "while" a certain criteria is met. The difference between a while and a do/while loop is that a do/while loop will always run at least once before it checks to see if the criteria needed to loop has been met.

//Googled Answer
"For loops":
The for loop is often the tool you will use when you want to create a loop.
for (code block to be executed before the loop; defines the condition for the loop; executed each time after the loop) {
    code block to be executed
}
The for loop repeats until a specified condition evaluates to false.

"While loops":
The while statement creates a loop that executes a specified statement as long as the test condition evaluates to true. The condition is evaluated before executing the statement.
The condition is an expression evaluated before each pass through the loop. If this condition evaluates to true, statement is executed. When condition evaluates to false, execution continues with the statement after the while loop.

10. How would you explain "scope" in javascript?

//Your Answer
Scope is the context in which a code is run or executed, in other words: where the variable can be seen by functions. There are two types of scopes: the global scope and the local scope. The global scope: would be things floating outside of functions, which is generally avoided because of the complications it may cause later on the the code. The local scope exists within the curly brackets of the function, and it cannot be accessed outside of this function. The local scope CAN access the variables and things that exists OUTSIDE of it's scope, but it cannot be accessed from the outside going in. (you can call IN items but items cannot be called OUT of the local scope)

//Googled Answer
JavaScript has function scope: Each function creates a new scope.
In JavaScript there are two types of scope:
Local scope
Global scope
Variables declared within a JavaScript function, become LOCAL to the function.
Local variables have local scope: They can only be accessed within the function
A variable declared outside a function, becomes GLOBAL.
A global variable has global scope: All scripts and functions on a web page can access it
Scope determines the accessibility of variables, objects, and functions from different parts of the code.
