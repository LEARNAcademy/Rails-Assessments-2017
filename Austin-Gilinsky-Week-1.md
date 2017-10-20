### Rails Course Assessment

## Week 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. What are ids and classes in css? Give your answer and write some css for the html below:

[Your Answer]
My answer: IDs are unique identifiers given to tags so you can style ceratin parts and you should not duplicate IDS.
Classes are also identifiers where you can style certain parts. You can have multiple classes with the same name.


[Googled Answer]
ID can be used to identify one element
Class can be used to identify more than one.

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
  background-color: blue;
  color: white;
  text-align: center;
}

.main-nav {
  background-color: black;
  font-size: 10px;
  font-style: italic;
}



#### 2. What is Bootstrap and why might you want to use it?


[Your Answer]
Bootsrap is a way to develope a responsive webpage.

[Googled Answer]
Bootstrap is the most popular HTML, CSS, and JS framework for developing responsive, mobile first projects on the web.


#### 3. Try to explain the css box model in your own words, as if to a friend who is learning css.

My Answer: The css box model is that everything on the page is a box. The middle is the content then padding then the border then the margin.

Googles Answer: The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content.


#### 4. What is the difference between a div and a span?

My Answer: Div- is a tag where you want to grab multiple sections of your html.
Span- is a tag where you only want to grab certain parts and style the html.

Googles Answer: The difference between span and div is that a span element is in-line and usually used for a small chunk of HTML inside a line (such as inside a paragraph) whereas a div (division) element is block-line (which is basically equivalent to having a line-break before and after it) and used to group larger chunks of code.


#### 5. What is "Semantic HTML"? Try to explain this concept and give 4 examples of semantic html tags.

My Answer: Semantic HTML helps show what is on the webpage.
Examles: <form> <table> <nav> <aritcle>

Googles Answer:Semantic HTML is the use of HTML markup to reinforce the semantics, or meaning, of the information in webpages and web applications rather than merely to define its presentation or look.


#### 6. The steps to pushing changes to a new git repo are laid out below - but they are out of order. Put them in the correct order. Feel free to try it out on your computer to confirm that you are right.

Run the command "git add ."
Create a new repo on your github account
Run "atom ." in the terminal and start working on the project
Set the remote the remote branch on your local project
Push to the new remote repo
Run the command "git commit -m "initial commit"

My Answer:
1.) Set the remote the remote branch on your local project
2.) Run "atom ." in the terminal and start working on the project
3.) Create a new repo on your github account
4.) Run the command "git add ."
5.) Run the command git commit -m initial commit
6.) Push to the new remote repo


#### 7. What is the "front-end"? What are some skills that would be important for front end developers to master? (You can list both hard and soft skills)
Front-end is what people see. HTML, CSS, and Javascript are a few of the skills you should master. Good communication and working well together are good soft skills to have.


#### 8. Fill in the css below to make the box have a 3px blue border, with text aligned to the center, and a background color of #eee.

```html
<div class="box">
    ....
</div>

<style>
.box {
  border-width: 3px;
  border-color: blue;
  text-align: center;
}
</style>
```


#### 9. Write four Terminal commands.
1.) status
2.) cd
3.) ls
4.) cd desktop


#### 10. What is your opinion of pair programming from what you've heard so far? Include some potential benefits or cons of pair programing.

I am in the middle with a pair programming. I like how you have more eyes to catch mistakes and another person to bounce ideas off of. But I do not like how the other person might always want to be in charge or listen to what you have to say. Their ego gets in the way.

#### 11. Javascript is a dynamically typed language - what does this mean?

My Answer:

Googles Answer: A language is dynamically typed if the type is associated with run-time values, and not named variables/fields/etc. This means that you as a programmer can write a little quicker because you do not have to specify types every time (unless using a statically-typed language with type inference). Example: Perl, Ruby, Python

#### 12. First, name 4 of the primitive data types in Javascript, then, write which javascript data type is not a primitive and why/what this means.

1.) Numbers
2.) Booleans
3.) Strings
4.)

#### 13. In your own words, try to explain what a variable is.

A variable is a something where we can store information for reuse.

#### 14. A function is provided for you below. First, alter the function so that your name would be logged out. Then, create a similar function that logs out a person's name and age.

```js

var myname = "name"

function printYourName(x){
    console.log("Hello " + x + "!")
}

printYourName(myname)

My Answer:

```
var myname = "Austin"
var myage = 29

function printYourName(x){
    console.log("Hello, My name is " + myname + " and I am " + myage + "!")
}

printYourName(myname)
