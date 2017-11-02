### Rails Course Assessment

## Week 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. What are ids and classes in css? Give your answer and write some css for the html below:

[Your Answer] Ids and classes are keywords we give to HTML tags in order to identify/differentiate them and then access those specific elements in CSS. They allow us to target certain tags and style them without modifying all the other elements with the same name (such as all divs). We use ids when we are targeting one specific element, and classes when we are targeting multiple elements (although they work in the same way). In CSS we use a "#" before Id names and "." before classes.

[Googled Answer] In CSS, selectors are patterns used to select the element(s) you want to style. The .class selector selects elements with a specific class attribute. To select elements with a specific class, write a period (.) character, followed by the name of the class. The #id selector styles the element with the specified id.

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
  margin: 10px;
  float: left;
  width: 175px;
}

.main-nav {
  background-color: limeGreen;
  font-family: fantasy;
  font-size: 2em;
}

#### 2. What is Bootstrap and why might you want to use it?

[Your Answer] Bootstrap is an HTML, CSS and JS library of pre-defined elements, classes, ids, tags, styles, themes and functionality that you link to your HTML file at the head. We can write our own additional CSS files to further customize these. One of the advantages of using it, is that you don't need to write every part of your project from the start; you can use pre-made and styled components such as buttons, nav bars, carousels, banners. It uses the CSS grid model to make your site responsive.

[Googled Answer] Bootstrap is an open source toolkit for developing with HTML, CSS, and JS. The world's most popular framework for building responsive, mobile-first sites. Advantages: Speed of Development, Responsiveness, Consistency, Customizable, Support.

#### 3. Try to explain the css box model in your own words, as if to a friend who is learning css.

[Your Answer] The CSS box model defines how content is placed within a page. A box wraps around every HTML element. So if we start from the center of the first box going outwards, we'd have the content and the space to the next box would be the padding, the space between that and the next box is the border, and finally the space between the border and the larger box (the whole page) is the margin. We use "padding", "border" and "margin" as properties in the CSS.

[Googled Answer] All HTML elements can be considered as boxes. In CSS, the term "box model" is used when talking about design and layout. The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. Explanation of the different parts:

    Content - The content of the box, where text and images appear
    Padding - Clears an area around the content. The padding is transparent
    Border - A border that goes around the padding and content
    Margin - Clears an area outside the border. The margin is transparent

#### 4. What is the difference between a div and a span?

[Your Answer] div creates a block that takes up space and can have more elements inside them. They are useful for making sections and for working with Bootstrap. span can be used inline to target specific parts of the content for example to change the color of just a few words. Both can use classes and ids.

[Googled Answer] The difference between span and div is that a span element is in-line and usually used for a small chunk of HTML inside a line (such as inside a paragraph) whereas a div (division) element is block-line (which is basically equivalent to having a line-break before and after it) and used to group larger chunks of code.

#### 5. What is "Semantic HTML"? Try to explain this concept and give 4 examples of semantic html tags.

[Your Answer] Semantic HTML was introduced in HTML5 with the purpose of making it more readable. They help identify certain parts of the code and make the use of divs + classes/ids less frequent. Examples: <nav>, <main>, <footer>, <section>.

[Googled Answer] A semantic element clearly describes its meaning to both the browser and the developer. Examples of non-semantic elements: <div> and <span> - Tells nothing about its content. Examples of semantic elements: <form>, <table>, <figure>, and <article> - Clearly defines its content.

#### 6. The steps to pushing changes to a new git repo are laid out below - but they are out of order. Put them in the correct order. Feel free to try it out on your computer to confirm that you are right.

Run "atom ." in the terminal and start working on the project
Run the command "git add ."
Run the command "git commit -m "initial commit"
Create a new repo on your github account
Set the remote branch on your local project
Push to the new remote repo

#### 7. What is the "front-end"? What are some skills that would be important for front end developers to master? (You can list both hard and soft skills)

Front-end is the part that is visible to the user. In the MVC, it refers to the view part.
Front-end skills:
  HTML/CSS
  Javascript/jQuery
  User Experience
  Responsive Design
  Soft skill: being adaptable, team player, sense of style, empathy

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
}
</style>

```

#### 9. Write four Terminal commands.

touch, ls, pwd, mv

#### 10. What is your opinion of pair programming from what you've heard so far? Include some potential benefits or cons of pair programing.

Pair programming is a tool used widely amongst developers which leads to better quality of code, focus, efficiency, and knowledge sharing. Although it may seem more comfortable to work on your own, working in pairs leads to a better result overall. Cons: working so closely with another person all day can be uncomfortable.

#### 11. Javascript is a dynamically typed language - what does this mean?

[Your Answer] It means that we don't have to specify the data type of each variable and that variables can be re-assigned at any point.

[Googled Answer] JavaScript is called a dynamic language because it doesn't just have a few dynamic aspects, pretty much everything is dynamic. All variables are dynamic (both in type and existence), and even the code is dynamic. You can create new variables at runtime, and the type of variables is determined at runtime. You can create new functions at any time, or replace existing functions. When used in a browser, code is added when more script files are loaded, and you can load more files any time you like. Nowadays JavaScript is compiled in many implementations, and static code and static types are generated in the background. However, the behavior is still dynamic, the compiler only generates static types when it finds that the dynamic aspects are not used for a specific object.

#### 12. First, name 4 of the primitive data types in Javascript, then, write which javascript data type is not a primitive and why/what this means.

4 primitive data types: boolean, string, number, null. They cannot be changed. Objects are not primitive data types and they have properties and methods (examples: Object, Date, Math, String, Number, RegExp, Array).

#### 13. In your own words, try to explain what a variable is.

A variable is created by using the word var and giving it a name or identifier (declaring a variable). It holds the value you assign to it (which can be reassigned at any point) and can be accessed when calling it anywhere in the code.

#### 14. A function is provided for you below. First, alter the function so that your name would be logged out. Then, create a similar function that logs out a person's name and age.

```js

var myname = "name"

function printYourName(x){
    console.log("Hello " + x + "!")
}

printYourName("Cris")

//

var name = "name";
var age = "age";

function personInfo(name, age) {
  console.log(name, age)
}

personInfo("John", 30)

```
