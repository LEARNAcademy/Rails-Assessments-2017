### Rails Course Assessment

## Week 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. What are ids and classes in css? Give your answer and write some css for the html below:

[IDs are selectors that manipulate a specific html item to change the styling of that item.  Classes - are selectors that manipulate multiple html its to change multiple stylings at once. Classes are selectors that manipulate multiple HTML items to change the styling of a group of items at the same time.]


[The #id selector styles the element with the specified id. - w3Schools. The .class selector selects elements with a specific class attribute.
To select elements with a specific class, write a period (.) character, followed by the name of the class.
You can also specify that only specific HTML elements should be affected by a class. To do this, start with the element name, then write the period (.) character, followed by the name of the class (look at Example 1 below).
HTML elements can also refer to more than one class (look at Example 2 below). - w3schools]

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

// #logo {
	width: 100px;
	height: 100px;

}

.main-nav {
	background-color: blue;
	color: white;
}



#### 2. What is Bootstrap and why might you want to use it?

[Bootstrap is an html, CSS, and javascript tool that allows you implement complex css code easier.  It’s great for creating templates sites a lot quicker and makes responsive design a lot easier to implement.]


[Build responsive, mobile-first projects on the web with the world's most popular front-end component library. Bootstrap is an open source toolkit for developing with HTML, CSS, and JS. Quickly prototype your ideas or build your entire app with our Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful plugins built on jQuery. - bootstrap]


#### 3. Try to explain the css box model in your own words, as if to a friend who is learning css.

[CSS box model allows a developer to structure a site with using a boxed grid to help the user easily consume the information in various styles and formats across various platforms.  It also helps design the HTML by wrapping the HTML in cleaner containers.]

[The CSS Box Model. All HTML elements can be considered as boxes. In CSS, the term "box model" is used when talking about design and layout. The CSS box modelis essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. - w3schools]


#### 4. What is the difference between a div and a span?

[a div is a non-semantic html element container that can be manipulated to a span is a non-semantic html element that allows a developer to manipulate specific text within a line of html code.]

[The difference between span and div is that a span element is in-line and usually used for a small chunk of HTML inside a line (such as inside a paragraph) whereas a div (division) element is block-line (which is basically equivalent to having a line-break before and after it) and used to group larger chunks of code. - w3Schools]


#### 5. What is "Semantic HTML"? Try to explain this concept and give 4 examples of semantic html tags.

[ Semantic HTML elements are parts of the html in HTML 5 that help structure an html page.  

<form>
<table>
<article>
<footer> ]

[A semantic element clearly describes its meaning to both the browser and the developer.]


#### 6. The steps to pushing changes to a new git repo are laid out below - but they are out of order. Put them in the correct order. Feel free to try it out on your computer to confirm that you are right.


Create a new repo on your github account
Run the command "git add ."
Run "atom ." in the terminal and start working on the project
Run the command "git commit -m "initial commit"
Set the remote branch on your local project
Push to the new remote repo



#### 7. What is the "front-end"? What are some skills that would be important for front end developers to master? (You can list both hard and soft skills)

[Front-end development refers developers being able to build and refine the view portion of a web program.  HTML, CSS, and Javascript are all codes that can be used to manipulate the client-side of a website.  A couple of skills that are important would be communicating the process in which code is being built, learning new technologies and new developments in the field. ]

[Front-end web development is the practice of producing HTML, CSS and JavaScript for a website or Web Application so that a user can see and interact with them directly. - wikipedia]

#### 8. Fill in the css below to make the box have a 3px blue border, with text aligned to the center, and a background color of #eee.

```html
<div class="box">
    ....
</div>

<style>
.box {
    border: 3px solid blue;
		text-align: center;
		background-color: #eee;
		color: #fff;
}
</style>

```


#### 9. Write four Terminal commands.

  [cd - change directory
   ls - list
   touch -
   mkdir]


#### 10. What is your opinion of pair programming from what you've heard so far? Include some potential benefits or cons of pair programing.

Paired programming is absolutely wonderful.  Having two people work on a specific project at the same time is really quite beneficial in that it helps the coder really understand the mistakes they are making while coding.  It also helps the director really focus and be able to teach each other what is going on.  It provides a solid way to understand the problem, approach the problem, and then guess and check on the spot.  

#### 11. Javascript is a dynamically typed language - what does this mean?

// a language that allows you to execute a piece of a code a little faster because it does not need a compiler to do any checking for code.  Which can be bad for many reasons as well

// Dynamically typed programming languages do type checking at run-time as opposed to Compile-time. - stack overflow

#### 12. First, name 4 of the primitive data types in Javascript, then, write which javascript data type is not a primitive and why/what this means.

  [Boolean
	string
	number
	undefined]

#### 13. In your own words, try to explain what a variable is.

[a variable is a container than that can store various types of data and be changed within a javascript context as the program is being moved along.]

#### 14. A function is provided for you below. First, alter the function so that your name would be logged out. Then, create a similar function that logs out a person's name and age.

```js

var myName = “name”;
function printYourName(name) {
  console.log(“Hello” +  name + “!”);
}
printYourName(“Greg”);

var myName = “name”, age = 31;
function printYourName(name, age) {
  console.log(“Hello” +  name + “!” + “You are “ + age + “ today!”);
}
printYourName(“Greg”, age);

```
