### Rails Course Assessment

## Week 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. What are ids and classes in css? Give your answer and write some css for the html below:

They allow you to call them in the css to style things that are under that class / id.


This allows you to set a particular style for many HTML elements with the same class. The class selector uses the HTML class attribute, and is defined with a "." id is used when we have to apply CSS property to one attribute only.

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
  clear: both;
  text-align: center;
}

.main-nav {
  float: right;
  border-bottom: #333 5px solid;
}



#### 2. What is Bootstrap and why might you want to use it?


Boot strap is a frame work that adds in pre built html / css themes. I would use this if the project was time sensitive and we need something up.


Bootstrap is a free and open-source front-end web framework for designing websites and web applications.


#### 3. Try to explain the css box model in your own words, as if to a friend who is learning css.

The box model is CSS that styles html elements. For things like height width or border.

The CSS Box Model. All HTML elements can be considered as boxes. In CSS, the term "box model" is used when talking about design and layout. The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content.


#### 4. What is the difference between a div and a span?

Divs divide a block of code. Spans are used for smaller things like a line.

The difference between span and div is that a span element is in-line and usually used for a small chunk of HTML inside a line (such as inside a paragraph) whereas a div (division) element is block-line (which is basically equivalent to having a line-break before and after it) and used to group larger chunks of code.


#### 5. What is "Semantic HTML"? Try to explain this concept and give 4 examples of semantic html tags.

Semantic HTML is using some of the tags below to help distinguish parts of code from others.

<header>
<h1>
<section>
<nav>

Semantic HTML is the use of HTML markup to reinforce the semantics, or meaning, of the information in webpages and web applications rather than merely to define its presentation or look. Semantic HTML is processed by traditional web browsers as well as by many other user agents.


#### 6. The steps to pushing changes to a new git repo are laid out below - but they are out of order. Put them in the correct order. Feel free to try it out on your computer to confirm that you are right.

Run the command "git add ."
Create a new repo on your github account
Run "atom ." in the terminal and start working on the project
Set the remote the remote branch on your local project
Push to the new remote repo
Run the command "git commit -m "initial commit"

1) Set the remote the remote branch on your local project
2) Create a new repo on your github account
3) Run the command "git add ."
4) Run the command "git commit -m "initial commit"
5) Run "atom ." in the terminal and start working on the project
6) Push to the new remote repo


#### 7. What is the "front-end"? What are some skills that would be important for front end developers to master? (You can list both hard and soft skills)

The view. What the users see / interact with.

Being able to think like the user and what you as a user would want.
Being creative in terms of designing.

#### 8. Fill in the css below to make the box have a 3px blue border, with text aligned to the center, and a background color of #eee.

```html
<div class="box">
    ....
</div>

<style>
.box {
  text-align: center;
  border: 3px blue solid;
  background-color: #eee;
}
</style>

```


#### 9. Write four Terminal commands.

cd / cd (name)
mkdir (name)
touch (name).(type)
atom .

#### 10. What is your opinion of pair programming from what you've heard so far? Include some potential benefits or cons of pair programing.

I personally enjoy pair programing. The ability to bounce ideas off each other is amazing. You may be stuck on something that your pair has an answer too.
Pros: Productivity, Staying on task, Brain power.
Cons: I can't think of any. :-}

#### 11. Javascript is a dynamically typed language - what does this mean?

Meaning when a JS file loads, it loads all could at once.

Dynamic programming language, in computer science, is a class of high-level programming languages which, at runtime, execute many common programming behaviors that static programming languages perform during compilation.

#### 12. First, name 4 of the primitive data types in Javascript, then, write which javascript data type is not a primitive and why/what this means.

String, number, boolean, undefined.

null - Null is nothing.

#### 13. In your own words, try to explain what a variable is.

variables are like a placeholder that stores data that you can then call for later.

#### 14. A function is provided for you below. First, alter the function so that your name would be logged out. Then, create a similar function that logs out a person's name and age.

```js

var myname = "name"

function printYourName(x){
    console.log(x)
}

printYourName(myname);

var name = "name"
var age = "age"

function nameAge(name, age) {
  console.log("Name:" + name "\nAge:" + age)
}

nameAge(name, age);

```
