### Rails Course Assessment

## Week 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. What are ids and classes in css? Give your answer and write some css for the html below:

[Your Answer]
ids: are identifiers that you can add to a tag in HTML that you will be able to reference on the CSS page. IDs are specifc and are only meant to be used once within the HTML document. 

classes: another type of identifier that can be used within the HTML to be referenced on the CSS page. The ID CAN be used multiple times (unlike IDs).

[Googled Answer]
The id selector uses the id attribute of an HTML element to select a specific element
The id of an element should be unique within a page, so the id selector is used to select one unique element!
You can use the same class on multiple elements.
You can use multiple classes on the same element.
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

.main-nav{
    background-color: blue;
    text-color: black;
}
#logo{
    text-color: grey;
    font-size: 3px;


#### 2. What is Bootstrap and why might you want to use it?


[Your Answer]
Boostrap is a downloadable plugin that gives you presets for buttons and headers and navigation bars. You can use it because it preformats your buttons and headers to look nice!

[Googled Answer]
Bootstrap is a free and open-source front-end web framework for designing websites and web applications. It contains HTML- and CSS-based design templates for typography, forms, buttons, navigation and other interface components, as well as optional JavaScript extensions. Unlike many web frameworks, it concerns itself with front-end development only.

#### 3. Try to explain the css box model in your own words, as if to a friend who is learning css.

[Your Answer]
The css box model is a way of thinking about how to positions elements within a webpage. It is as if the whole screen was divided into 12 squares and so the components of the page would have square sizes that add up to equal 12. 
[Googled Answer]
All HTML elements can be considered as boxes. In CSS, the term "box model" is used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content

#### 4. What is the difference between a div and a span?

[Your Answer]
A div is 
[Googled Answer]


#### 5. What is "Semantic HTML"? Try to explain this concept and give 4 examples of semantic html tags.

[Your Answer]
Semantic HTML is HTML tags whose names give an idea of what that block of code is meant for or is doing. Semantic tags include: header, footer, nav, section. 
[Googled Answer]
A semantic element clearly describes its meaning to both the browser and the developer. Semanti elements are elements with a meaning. 
Common semantic HTML: article, figure, footer, main, etc. 

#### 6. The steps to pushing changes to a new git repo are laid out below - but they are out of order. Put them in the correct order. Feel free to try it out on your computer to confirm that you are right.

Run "atom ." in the terminal and start working on the project
Run the command "git add ."
Run the command "git commit -m "initial commit"
Create a new repo on your github account
Set the remote the remote branch on your local project
Push to the new remote repo


#### 7. What is the "front-end"? What are some skills that would be important for front end developers to master? (You can list both hard and soft skills)
The "front-end" refers to whatever the users are going to see or interact with. Front end developers should master HTML and CSS and Javascript to make things more interactive. They should also know how to use bootstrap with html and css. 

#### 8. Fill in the css below to make the box have a 3px blue border, with text aligned to the center, and a background color of #eee.

```html
<div class="box">
    ....
</div>

<style>
.box {
    border-color: blue;
    border-width: 3px;
    background-color: #eee;
    text-align: center;
}
</style>

```


#### 9. Write four Terminal commands.
cd
ls
open .
mkdir

#### 10. What is your opinion of pair programming from what you've heard so far? Include some potential benefits or cons of pair programing.
Pair programming is useful because having two sets of eyes on one computer means more mistakes will be caught (like typos or missing brackets) and you also have two brains thinking about the same problem so you may be more likely to come to a comclusion faster. Some potential cons are that there would be disagreements in handling a problem, difficulty in communication or personality types which could cause conflicts. But so far I like pair programming, I think that it has been helpful to have two people working on the same computer, especially when one of us gets stuck there is someone else to bring in some of their insight as well.

#### 11. Javascript is a dynamically typed language - what does this mean?

// your answer

// googled answer
Most dynamic languages are also dynamically typed, but not all are. Dynamic languages are frequently (but not always) referred to as "scripting languages", although the term "scripting language" in its narrowest sense refers to languages specific to a given run-time environment.

#### 12. First, name 4 of the primitive data types in Javascript, then, write which javascript data type is not a primitive and why/what this means.

#### 13. In your own words, try to explain what a variable is. 
A variable is stored information that you are able to call upon request by the variable name. 

#### 14. A function is provided for you below. First, alter the function so that your name would be logged out. Then, create a similar function that logs out a person's name and age.

```js

var myname = "Kari Ann"

function printYourName(x){
    console.log("Hello " + x + "!")
}

printYourName(myname)

var myname = "Kari Ann"
var age = 23

function printYourNameAge (x,y){
    console.log("My name is " + x + "and I am " + y + "years old!")
}

printYourNameAge(myname, age)
```


