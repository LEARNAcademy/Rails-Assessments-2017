### Rails Course Assessment

## Week 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. What are ids and classes in css? Give your answer and write some css for the html below:

[Your Answer]

Both are used to classify parts of the html code. Ids are used for just one thing while classes can be used across multiple things.

[Googled Answer]

Unlike the id selector, the class selector is most often used on several elements. This allows you to set a particular style for many HTML elements with the same class. The class selector uses the HTML class attribute, and is defined with a "." idis used when we have to apply CSS property to one attribute only.

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

#id {
  font-family: fantasy;
  color: blue;
  background-color: LightGrey
}

.logo {
  border-style: solid;
  padding: 20px;
  margin: 20px;
}

#### 2. What is Bootstrap and why might you want to use it?


[Your Answer]

A bunch of ready to use html code u can plug in for styling

[Googled Answer]

Bootstrap is a free and open-source front-end web framework for designing websites and web applications. It contains HTML- and CSS-based design templates for typography, forms, buttons, navigation and other interface components, as well as optional JavaScript extensions.

#### 3. Try to explain the css box model in your own words, as if to a friend who is learning css.

[Your Answer]

the box model is a positioning style where things are positioned with box-shaped borders around each piece of it.

[Googled Answer]
The CSS Box Model. All HTML elements can be considered as boxes. In CSS, the term "box model" is used when talking about design and layout. The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content


#### 4. What is the difference between a div and a span?

[Your Answer]

A div targets larger sections of html while a span targets smaller pieces

[Googled Answer]

The difference between span and div is that a span element is in-line and usually used for a small chunk of HTML inside a line (such as inside a paragraph) whereas a div (division) element is block-line (which is basically equivalent to having a line-break before and after it) and used to group larger chunks of code.

#### 5. What is "Semantic HTML"? Try to explain this concept and give 4 examples of semantic html tags.

[Your Answer]

Semantic HTML is html code that uses meaningful tags like "table" rather than "div". they explain what they do. 4 examples: tables, <p>, <header>, <footer>

[Googled Answer]

 Semantic HTML is the use of HTML markup to reinforce the semantics, or meaning, of the information in webpages and web applications rather than merely to define its presentation or look.

#### 6. The steps to pushing changes to a new git repo are laid out below - but they are out of order. Put them in the correct order. Feel free to try it out on your computer to confirm that you are right.

Set the remote the remote branch on your local project
Run "atom ." in the terminal and start working on the project
Create a new repo on your github account
Run the command "git add ."
Run the command "git commit -m "initial commit"
Push to the new remote repo


#### 7. What is the "front-end"? What are some skills that would be important for front end developers to master? (You can list both hard and soft skills)

front end is what the users see and interact w/. making things user-friendly, look nice, use organized code, and know the ins and outs of html, css, javascript, and bootstrap.

#### 8. Fill in the css below to make the box have a 3px blue border, with text aligned to the center, and a background color of #eee.

```html
<div class="box">
    ....
</div>

<style>
.box {

}
</style>

```
.box {
  border-color: blue;
  border-width: 3px;
  background-color: #eee;
  text-align: center;
}

#### 9. Write four Terminal commands.

cd
mkdir
atom .
ls


#### 10. What is your opinion of pair programming from what you've heard so far? Include some potential benefits or cons of pair programing.

I like it because it seems to enforce focus and teaches us how to work with other people's personalities and quirks. These are benefits, and others are that it increases learning and productivity. Cons are if one person tries to run the show and doesn't respect the pair-programming rules, or if the pair is closed to the other's style.

#### 11. Javascript is a dynamically typed language - what does this mean?

// your answer

I'm not sure.

// googled answer

A programming language is said to be dynamically typed, or just 'dynamic', when the majority of its type checking is performed at run-time as opposed to at compile-time. In dynamic typing, types are associated with values not variables.

#### 12. First, name 4 of the primitive data types in Javascript, then, write which javascript data type is not a primitive and why/what this means.

string
number
boolean
undefined

a symbol is not primitive.


#### 13. In your own words, try to explain what a variable is.

A variable is a value which is assigned to a data type.

#### 14. A function is provided for you below. First, alter the function so that your name would be logged out. Then, create a similar function that logs out a person's name and age.

```js

var myname = "Veronica"

function printYourName(x){
    console.log("Hello " + x + "!")
}

printYourName(myname)


// x should equal the string of someone's name, and y should be the age
function printNameAndAge(x, y) {
  console.log("This is " + x + " who is " + y + " years old.")
}

printNameAndAge("Veronica", 33);
```
