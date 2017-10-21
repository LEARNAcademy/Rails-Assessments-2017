### Rails Course Assessment

## Week 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.


#### 1. What are ids and classes in css? Give your answer and write some css for the html below:

[Your Answer]
ids and classes are classifications that we give to a block of code that CSS understands and can call on to alter the appearance of those blocks of code.

[Googled Answer]
Id and class "selectors" are used to specify styles for elements of HTML. Unlike the id selector, the class selector is most often used on several elements. This allows you to set a particular style for many HTML elements with the same class.

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <link type="text/css" rel="stylesheet" href="assessment1.css"> </link>
        <title>Assessment1</title>
    </head>
    <body>
        <header>
            <div id="logo">This will be a logo</div>
        </header>
        <p class="text">This is some text that looks different from normal.</p>
    </body>
</html>
```

#logo {
  font-family: Helvetica;
  font-size: 200%;
  color: forestgreen;
  text-align: center;
}
.text {
  font-family: sans-serif sans-serif;
  font-size: 120%;
  color: blue;
  text-align: right;
}

#### 2. What is Bootstrap and why might you want to use it?

[Your Answer]
Bootstrap is a collection of pre-styled CSS sheets that you can use to stylize your HTML. A major benefit of using Bootstrap is that you don't have to build your CSS from the ground up.

[Googled Answer]
"Bootstrap is a free and open-source front-end web framework for designing websites and web applications. It contains HTML- and CSS-based design templates for typography, forms, buttons, navigation and other interface components, as well as optional JavaScript extensions."

#### 3. Try to explain the css box model in your own words, as if to a friend who is learning css.

[Your Answer]
The CSS model dictates that everything you can alter using CSS (elements: text, pictures, headers, buttons, etc.) is inside of a box, and you can alter different elements of that box. You can choose a border style, color, width etc., you can specify how far away (in pixels) you want a block of text to be from a picture, the list goes on and on. It has a lot to do with the space between elements.

[Googled Answer]
"The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content."

#### 4. What is the difference between a div and a span?

[Your Answer]
Divs allow you to assign a particular style of CSS to a block of code, where spans allow you to alter text in line.

[Googled Answer]
"The difference between span and div is that a span element is in-line and usually used for a small chunk of HTML inside a line (such as inside a paragraph) whereas a div (division) element is block-line (which is basically equivalent to having a line-break before and after it) and used to group larger chunks of code."

#### 5. What is "Semantic HTML"? Try to explain this concept and give 4 examples of semantic html tags.

[Your Answer]
Semantic HTML is a collection of tags that create blocks of code that are descriptive in name. They operate similarly to divs, but make your code easier to read and understand. Examples are the header, footer, aside and article tags.

[Googled Answer]
"Semantic HTML is the use of HTML markup to reinforce the semantics, or meaning, of the information in webpages and web applications rather than merely to define its presentation or look."

#### 6. The steps to pushing changes to a new git repo are laid out below - but they are out of order. Put them in the correct order. Feel free to try it out on your computer to confirm that you are right.

Run "atom ." in the terminal and start working on the project
Run the command "git add ."
Create a new repo on your github account
Run the command "git commit -m "initial commit"
Set the remote the remote branch on your local project
Push to the new remote repo

#### 7. What is the "front-end"? What are some skills that would be important for front end developers to master? (You can list both hard and soft skills)
The "front-end" is the skeleton (HTML) and design (CSS) of a website (as well as some interactivity elements). Hard skills for front-end development would be being proficient in both HTML and CSS. Soft skills would be being somewhat artistically inclined so that one can create a visually appealing and intuitive user interface.

#### 8. Fill in the css below to make the box have a 3px blue border, with text aligned to the center, and a background color of #eee.

```html
<div class="box">
    <p>This is my box.</p>
</div>

<style>
.box {
border-width: 3px;
border-color: blue;
text-align: center;
background-color: #eee;
}
</style>

```

#### 9. Write four Terminal commands.
cd
mkdir
pwd
ls

#### 10. What is your opinion of pair programming from what you've heard so far? Include some potential benefits or cons of pair programing.
Pair programming is great in my opinion, having a very limited background in coding I get to pair with people who for the most part know more than I do and can help explain concepts if I don't understand them. Also, if one person gets stuck on one thing the two can put their heads together to solve the problem together. Some cons would be if the pair doesn't approach problems in the same way that can be a block in regards to teamwork, or if the pair have very different ideas when it comes to the direction they want to take in order to complete a task.

#### 11. Javascript is a dynamically typed language - what does this mean?

[Kiah's answer]
JavaScript is both an object oriented and functionally oriented. It reads its code line by line as opposed to having a whole program compiled before running. JavaScript is like a Jack of all trades but a master of none.

[Google's answer]
JavaScript is weakly typed, meaning that its nature allows for a lot of flexibility in terms of implicit conversions. Being dynamically typed means that the majority of its type checking is performed at run-time as opposed to at compile-time.

#### 12. First, name 4 of the primitive data types in Javascript, then, write which javascript data type is not a primitive and why/what this means.
Number, string, Boolean, and undefined are all primitive data types. Objects are the only data type that is not primitive because, unlike the primitives, it can store multiple values inside of it.

#### 13. In your own words, try to explain what a variable is.
A variable is a named storage location in the memory of the computer that one can set to store the data that they choose.

#### 14. A function is provided for you below. First, alter the function so that your name would be logged out. Then, create a similar function that logs out a person's name and age.

```js

var myname = "Kiah"

function printYourName(x){
    console.log("Hello " + x + "!")
}

printYourName(myname)

//

function printNameAndAge (name, age) {
  var name = prompt("Please enter your name");
  var age = prompt("Please enter your age");
  console.log("Your name is "+name+" and your age is "+age);
}
printNameAndAge();
