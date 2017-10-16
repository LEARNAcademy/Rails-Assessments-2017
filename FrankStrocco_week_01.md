

Frank Strocco
Week one Assessment


1. What are ids and classes in css? Give your answer and write some css
 for the html below:

[Your Answer]

Classes and Ids in Your html allow you to specify your selectors on your css.
classes can be used an unlimited time. ids can only be used once
you can add them to most any html tag.. divs spans p img..ect..


----------

[Googled Answer]

Unlike the id selector, the class selector is most often used on several
elements. This allows you to set a particular style for many HTML elements
with the same class. The class selector uses the HTML class attribute,
and is defined with a "." id is used when we have to apply CSS property to
one attribute only.

----------

<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title></title>

        <style>
          #logo {
            font-family: Helvetica;
            font-weight: bold;
            color: blue;
          }
          .main-nav {
            padding: 15px 20px;
            color: lightblue;
            background-color: #999;
          }

        </style>
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
-----------------

2. What is Bootstrap and why might you want to use it?

[Your Answer]

Bootstrap is mainly for building responsive websites and is kind of a
frame work. Prebuilt templetes of html and ready for class and
ids to define how it will make your pages look. Built on a 12 column layout.

---------
[Googled Answer]


It is an HTML, CSS, javascript framework that you can use as a basis for
creating web sites or web applications.

Bootstrap is the most popular HTML, CSS, and JS framework for developing
responsive, mobile first projects on the web.
----------

3. Try to explain the css box model in your own words, as if to a friend
who is learning css.

[Your Answer]

css has a "box model" it looks like several boxes inside each other that can be
defined by size. they react to each other and the elements around them. They
start with the content on the inside then go out..with padding, then border which
is visible, then margin which controls how far away your box sits or stays away
from other obects..pictures or other boxs..ect..
---

[Googled Answer]

All HTML elements can be considered as boxes. In CSS, the term "box model" is
 used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element.
It consists of: margins, borders, padding, and the actual content.
Explanation of the different parts:

Content - The content of the box, where text and images appear
Padding - Clears an area around the content. The padding is transparent
Border - A border that goes around the padding and content
Margin - Clears an area outside the border. The margin is transparent


--------
4. What is the difference between a div and a span?

[Your Answer]

A div is a html element that is block level, where a span element is in line
either can hold id or class one block usually returns a line where as the span
does not.
----
[Googled Answer]

The difference between span and div is that a span element is in-line and
usually used for a small chunk of HTML inside a line (such as inside a paragraph)
whereas a div (division) element is block-line (which is basically equivalent
to having a line-break before and after it) and used to group larger chunks
of code.

-----
5. What is "Semantic HTML"? Try to explain this concept and give 4 examples
 of semantic html tags.

[Your Answer]

a semantic element explains to the browser what it contains and helps organize
the html code. Especially for accessablitly.
main html tag footer tag header tag, h1 tag
-------
[Googled Answer]

A semantic element clearly describes its meaning to both the browser and
 the developer. Examples of non-semantic elements: <div> and <span> -
  Tells nothing about its content. Examples of semantic elements: <form>,
   <table>, and <article> - Clearly defines its content.
---------

6. The steps to pushing changes to a new git repo are laid out below - but they
 are out of order. Put them in the correct order. Feel free to try it out on
  your computer to confirm that you are right.

Run the command "git add ." Create a new repo on your github account Run "atom ."
 in the terminal and start working on the project Set the remote the remote branch
  on your local project Push to the new remote repo Run the command "git commit -m""
   "initial commit""

-first -- Run "atom ." in the terminal and start working on the project
-second-- Set the remote the remote branch on your local project "git init"
-third--  Run the command "git add ."
-fourth-- Create a new repo on your github account
-fifth -- Push to the new remote repo
-sixth -- Run the command "git commit -m "initial commit"

"

------
7. What is the """"front-end? What are some skills that would be important for
front end developers to master? (You can list both hard and soft skills)

front-end refers to the viewable webpage that the user sees. A front and web developer
would do best to be well skilled in HTML CSS and Javascript. Design would come in handy. As well as
some photoshop skills.


8. Fill in the css below to make the box have a 3px blue border, with text aligned
 to the center, and a background color of #eee.

<div class="box">
    ....
</div>

<style>
.box {
  border: 3px solid blue;
  text-align: center;
  background-color: #eee;
}
</style>
9. Write four Terminal commands.
ls
mkdir newFolder
pwd
touch newFile
cd ../

10. What is your opinion of pair programming from what you've heard so far? Include'
 some potential benefits or cons of pair programing.''

Pair programming is better then I thought it would be. As long as its 2 people
and not 3. Its faster overall. less mistakes go un-noticed. You get the best of
both programmers. One could be better in a certain area and same with the other.
combine those and you have 2 strong areas instead of one.

cons .. Sometimes you get a person that wants to "run the show" You have to calm
them down and try to get them to work as a team


11. Javascript is a dynamically typed language - what does this mean?''

// your answer'
I thought the term was losely typed language, but i think theres several terms
for different languages. I would say that a dynamically typed language works
well even with mistakes in syntax(that might be losely typed) it also works well
with many other languages.


-----------
// googled answer
I was way off ;D

In dynamically-typed languages, the errors occur only once the program is
executed. That is, at runtime. This means that a program written in a
dynamically-typed language (like JavaScript or Python) can compile even
if it contains type errors that would otherwise prevent the script from
running properly.


---------------
12. First, name 4 of the primitive data types in Javascript, then, write which
javascript data type is not a primitive and why/what this means.
1. strings
2. boleans
3. integers
4. symbols

objects are not primative because they have properties and can run methods/functions
directly on them.

----------
// googled answer
Boolean.
Null.
Undefined.
Number.
String.
Symbol (new in ECMAScript 6)
The variable will then store data as a string of characters. Non-primitive
data types are not defined by the programming language, but are instead created
 by the programmer. They are sometimes called "reference variables," or "object
 references," since they reference a memory location, which stores the data


13. In your own words, try to explain what a variable is.

a temporary storage holder. it takes a data type and can hold it in different
ways depending on its scope.
----

14. A function is provided for you below. First, alter the function so that your
name would be logged out. Then, create a similar function that logs out a person's
name and age.

var myname = "Frank"

function printYourName(x){
    console.log("Hello " + x + "!")
}

printYourName(myname)

var myName = prompt("what's your name");
var myAge = prompt("what's your age");

function yourNameAge(){
  console.log(myName + " wishes he/she was " + myAge + " years old")
}

yourNameAge();
