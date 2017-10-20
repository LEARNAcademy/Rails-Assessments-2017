### Rails Course Assessment

## Week 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. What are ids and classes in css? Give your answer and write some css for the html below:

[Your Answer]
Ids and classes are used to denote which elements of an html page to style. ids are assigned using id= and called upon in css using a "#" Classes are assigned using class= and called upon in css using a "."

[Googled Answer]
Use a class when you want to consistently style multiple elements throughout the page/site. Classes are useful when you have, or possibly will have in the future, more than one element that shares the same style. An example may be a div of "comments" or a certain list style to use for related links.
Use the ID when you have a single element on the page that will take the style. Remember that IDs must be unique. In your case this may be the correct option, as there presumably will only be one "main" div on the page.

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title></title>
    </head>
    <body>
        <header>
            <div id="logo">This will be a logo</div>
            <nav class="main-nav">
                  ....
            </nav>
        </header>
    </body>
</html>
```

You write the CSS

// write some css for the class and id in the html above (two or three properties per id/class is sufficient)
#logo {
  color: black;
  font-family: fantasy;
  font-size: 10px;
}

.main {
  float: left;
  background-color: blue;
  border: solid black 2px;
}

#### 2. What is Bootstrap and why might you want to use it?

[Your Answer]
Bootstrap is a set of premade html code that is easy to swap in and out and alter. This is helpful for quickly setting up common webpage features.

[Googled Answer]
Bootstrap is a free front-end framework for faster and easier web development
Bootstrap includes HTML and CSS based design templates for typography, forms, buttons, tables, navigation, modals, image carousels and many other, as well as optional JavaScript plugins
Bootstrap also gives you the ability to easily create responsive designs

#### 3. Try to explain the css box model in your own words, as if to a friend who is learning css.

[Your Answer]
Every part of code that is viewable in the DOM has inherent characteristics like size and spacing. the CSS box model gives a way to manipulate these characteristics. the most obvious example is the margins which either push the element away or allow the element to be closer to other parts of the webpage.

[Googled Answer]
All HTML elements can be considered as boxes. In CSS, the term "box model" is used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. 

#### 4. What is the difference between a div and a span?

[Your Answer]
Divs divide up sections of HTML to make it more clear and easier to assign styles. They do not actually show on the view.
I don't remember what a span is.

[Googled Answer]
The difference between span and div is that a span element is in-line and usually used for a small chunk of HTML inside a line (such as inside a paragraph) whereas a div (division) element is block-line (which is basically equivalent to having a line-break before and after it) and used to group larger chunks of code.

#### 5. What is "Semantic HTML"? Try to explain this concept and give 4 examples of semantic html tags.

[Your Answer]
<section>
<nav>
<header>
<footer>

Semantic HTML helps break out what code is what in HTML. These can help assign ids and classes to larger sections of the page making it easier to conceptualize and execute styles and manipulations.

[Googled Answer]
Semantic HTML is the use of HTML markup to reinforce the semantics, or meaning, of the information in webpages and web applications rather than merely to define its presentation or look. Semantic HTML is processed by traditional web browsers as well as by many other user agents. CSS is used to suggest its presentation to human users.

#### 6. The steps to pushing changes to a new git repo are laid out below - but they are out of order. Put them in the correct order. Feel free to try it out on your computer to confirm that you are right.

Run "atom ." in the terminal and start working on the project
Run the command "git add ."
Run the command "git commit -m "initial commit"
Create a new repo on your github account
Set the remote branch on your local project
Push to the new remote repo

A few of these steps can be out of order and still work. (e.g. create a new repo)

#### 7. What is the "front-end"? What are some skills that would be important for front end developers to master? (You can list both hard and soft skills)

Front end is the view of the webpage. In other words, it is what the user sees while online. front end developers should be able to make intuitive, pleasant designs and utilize javascript to make the page interactive.


#### 8. Fill in the css below to make the box have a 3px blue border, with text aligned to the center, and a background color of #eee.

```html
<div class="box">
    ....
</div>

<style>
.box {
  border: blue solid 3px;
  text-align: center;
  background-color: #eee;
}
</style>

```


#### 9. Write four Terminal commands.
ls
mkdir
cd ..
touch

#### 10. What is your opinion of pair programming from what you've heard so far? Include some potential benefits or cons of pair programing.

I enjoy pair programming so far. It helps the developers maintain focus. Working with someone else can lead to new discoveries.

#### 11. Javascript is a dynamically typed language - what does this mean?

// your answer
a dynamic language is one that has more inherent logic baked into it so the user does not have to do everything. the language will calculate some parts of the code without having to go down to the basic computer level.

// googled answer
Dynamic programming language, in computer science, is a class of high-level programming languages which, at runtime, execute many common programming behaviors that static programming languages perform during compilation.

#### 12. First, name 4 of the primitive data types in Javascript, then, write which javascript data type is not a primitive and why/what this means.
Number
String
Boolean
Undefined

variable - this can be changed to something else.

#### 13. In your own words, try to explain what a variable is.
A variable is a piece of data that can be set to anything. Variables are mainly used in functions to help execute certain commands. These pieces of data can be rewritten, allowing the user to accomplish complex actions.

#### 14. A function is provided for you below. First, alter the function so that your name would be logged out. Then, create a similar function that logs out a person's name and age.

```js

var myname = "Tim Petrone";

function printYourName(x){
    console.log("Hello " + x + "!")
};

printYourName(myname);

var name = "Tim Petrone";
var age = 26;

function nameAge (x, y) {
  console.log(x + " is " + y + " years old.")
};

```
