### Rails Course Assessment

## Week 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. What are ids and classes in css? Give your answer and write some css for the html below:

[Your Answer]
Ids: target individual elements for css. Classes: target elements that will share the same characteristics.

[Googled Answer]
The difference between an ID and a class is that an ID can be used to identify one element, whereas a class can be used to identify more than one.

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
#logo {
  font-weight: bold;
  font-color: red;
  font-family: fantasy;
}
.main-nav {
  align-text: center;
  background-color: light-blue;
};
// write some css for the class and id in the html above (two or three properties per id/class is sufficient)



#### 2. What is Bootstrap and why might you want to use it?


[Your Answer]
Bootstrap is a tool for HTML/CSS used to bring previously written code with certain tools such as nav bars, ect.

[Googled Answer]
Bootstrap is a free and open-source front-end web framework for designing websites and web applications. It contains HTML- and CSS-based design templates for typography, forms, buttons, navigation and other interface components, as well as optional JavaScript extensions.

#### 3. Try to explain the css box model in your own words, as if to a friend who is learning css.

[Your Answer]
Each part of the page is separated into varying boxes, which contain a margin, border, padding, and actual content.
[Googled Answer]
Explanation of the different parts:

Content - The content of the box, where text and images appear
Padding - Clears an area around the content. The padding is transparent
Border - A border that goes around the padding and content
Margin - Clears an area outside the border. The margin is transparent

#### 4. What is the difference between a div and a span?

[Your Answer]
Spans usually separate small amounts of code. Maybe within a paragraph. Divs are for larger blocks of code.
[Googled Answer]
The difference between span and div is that a span element is in-line and usually used for a small chunk of HTML inside a line (such as inside a paragraph) whereas a div (division) element is block-line (which is basically equivalent to having a line-break before and after it) and used to group larger chunks of code.

#### 5. What is "Semantic HTML"? Try to explain this concept and give 4 examples of semantic html tags.

[Your Answer]
Reinforces the meaning of the HTML code you write. Ex. form, section, article, table.
[Googled Answer]
Semantics is the study of the meanings of words and phrases in a language.

Semantic elements = elements with a meaning.

#### 6. The steps to pushing changes to a new git repo are laid out below - but they are out of order. Put them in the correct order. Feel free to try it out on your computer to confirm that you are right.

Run "atom ." in the terminal and start working on the project
Create a new repo on your github account
Set the remote the remote branch on your local project
Run the command "git add ."
Run the command "git commit -m "initial commit"
Push to the new remote repo

#### 7. What is the "front-end"? What are some skills that would be important for front end developers to master? (You can list both hard and soft skills)
Front end means the programmer is more focused on the users experience: what they see, the design, ect. It is important to master HTML, CSS, JavaScript, recognizing what makes a good user experience, ect.

#### 8. Fill in the css below to make the box have a 3px blue border, with text aligned to the center, and a background color of #eee.

```html
<div class="box">
    ....
</div>

<style>
.box {
text-align: center;
border-width: 3px;
border-color: blue;
background-color: #eee;
}
</style>

```


#### 9. Write four Terminal commands.
mkdir
cd
Clear
touch

#### 10. What is your opinion of pair programming from what you've heard so far? Include some potential benefits or cons of pair programing.
Pair programming is nice because both people bring their individual skills to the table which allows for a better learning experience. It is also faster than coding individually and you keep each other in check.
#### 11. Javascript is a dynamically typed language - what does this mean?

// your answer
JavaScript runs from top to bottom and can still run if part of it is broken.
// googled answer
Dynamically typed programming languages do type checking at run-time as opposed to Compile-time.
#### 12. First, name 4 of the primitive data types in Javascript, then, write which javascript data type is not a primitive and why/what this means.
Boolean, Null, String, Undefined.
var word = newString. Objects are not primitive.
#### 13. In your own words, try to explain what a variable is.
A variable is something you use to store a value or method.
#### 14. A function is provided for you below. First, alter the function so that your name would be logged out. Then, create a similar function that logs out a person's name and age.

```js

var myname = "name"

function printYourName(x){
    console.log(x " " + "is logged out.")
}

printYourName(myname)

var myname = "name"

function printYourNameandAge(x, y){
    console.log(x " " + "is aged" " " + y)
}

printYourName(myname)

```
