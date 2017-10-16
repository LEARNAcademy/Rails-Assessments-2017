### Rails Course Assessment

## Week 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. What are ids and classes in css? Give your answer and write some css for the html below:

[Your Answer]
ID's are selected by the # sign and pertain to a specific object that should only be used once.
Classes are selected by adding a . before the class name. they can be used to specify multiple objects and used more than once. 

[Googled Answer]

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
 margin: 5px;
 color: black;
 }
.main-nav {
 padding: 5px;
 background-color: gray;
 }
 
#### 2. What is Bootstrap and why might you want to use it?


[Your Answer]
Bootstrap is a javascript framework that allows you to quickly develop interactive websites that have functional html,css,javascript. It is limited in what you can do however it is easy to quickly deploy.

[Googled Answer]


#### 3. Try to explain the css box model in your own words, as if to a friend who is learning css.

[Your Answer]
Refers to the design and layout used in CSS. The box model allows for simpler organization of objects.

[Googled Answer]


#### 4. What is the difference between a div and a span?

[Your Answer]
Span is "in-line" whereas a DIV is "block-line". Span is used in a line of html typically and a DIV is more of a container type tool.
[Googled Answer]


#### 5. What is "Semantic HTML"? Try to explain this concept and give 4 examples of semantic html tags.

[Your Answer]
Semantic means that it is actually doing something by itself just by being there. <strong> <table> <article> <form>
[Googled Answer]


#### 6. The steps to pushing changes to a new git repo are laid out below - but they are out of order. Put them in the correct order. Feel free to try it out on your computer to confirm that you are right.

Run "atom ." in the terminal and start working on the project
Create a new repo on your github account
Run the command "git add ."
Run the command "git commit -m "initial commit"
Set the remote the remote branch on your local project
Push to the new remote repo

#### 7. What is the "front-end"? What are some skills that would be important for front end developers to master? (You can list both hard and soft skills)
Front end is what the user will view. Design and skills with front end tools like javascript,css, html are important. I would say this portion is heavy on UI/UX.

#### 8. Fill in the css below to make the box have a 3px blue border, with text aligned to the center, and a background color of #eee.

```html
<div class="box">
    ....
</div>

<style>
.box {
 border: 3px blue;
 text-align: center;
 background-color: #eee;
}
</style>

```


#### 9. Write four Terminal commands.
mkdir, touch, cd, ls

#### 10. What is your opinion of pair programming from what you've heard so far? Include some potential benefits or cons of pair programing.
I am a big fan of it. ask Adam Cuppy lol
#### 11. Javascript is a dynamically typed language - what does this mean?

// your answer
had to google this one for clarity.
// googled answer
 language is dynamically typed if the type is associated with run-time values, and not named variables/fields/etc. This means that you as a programmer can write a little quicker because you do not have to specify types every time (unless using a statically-typed language with type inference). Example: Perl, Ruby, Python


#### 12. First, name 4 of the primitive data types in Javascript, then, write which javascript data type is not a primitive and why/what this means.
Boolean , Number, String, Symbol

Object is not a primitive data type

#### 13. In your own words, try to explain what a variable is. 
a variable is a value that we declare with a name. 
#### 14. A function is provided for you below. First, alter the function so that your name would be logged out. Then, create a similar function that logs out a person's name and age.

```js

var myName = "nick"
var myAge = "27"

function printYourInfo(x,y){
    console.log("Hello " + x + y + "!")
}

printYourInfo(myName, myAge)

```


