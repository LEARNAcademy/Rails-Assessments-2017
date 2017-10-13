Week 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

1. What are ids and classes in css? Give your answer and write some css for the html below:

[Your Answer]
Ids and classes allow you to apply css properties to elements in html by linking to the css doc as a stylesheet in the html doc. An id lets you apply css properties to just one element in the html that has that id in its tag. A class is similar, but lets you apply the same css properties to multiple elements in the html that each have that class in their tags.

[Googled Answer]
ID's are unique. Each element can have only one ID. Each page can have only one element with that ID.
Classes are NOT unique. You can use the same class on multiple elements. You can use multiple classes on the same element. Any styling information that needs to be applied to multiple objects on a page should be done with a class.

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
You write the CSS

// write some css for the class and id in the html above (two or three properties per id/class is sufficient)

#logo {
  color: red;
  font-family: helvetica;
  background-image: images/cool-image.jpg
}
.main-nav {
  background-color: green;
  border-style: solid;
  margin: 5px;
}

2. What is Bootstrap and why might you want to use it?

[Your Answer]
Bootstrap is an online resource that allows you to download or link to pre-made styles, website templates, or other code for use in your own webpage/web app without having to start from scratch each time.

[Googled Answer]
Bootstrap is a free and open-source front-end web framework for designing websites and web applications. It contains HTML- and CSS-based design templates for typography, forms, buttons, navigation and other interface components, as well as optional JavaScript extensions. Unlike many web frameworks, it concerns itself with front-end development only.

3. Try to explain the css box model in your own words, as if to a friend who is learning css.

[Your Answer]
Every element displayed on a webpage takes up some amount of horizontal and vertical space. When something on a page is loaded with all its linked css attributes, it and the space around it will create a box of a certain size in which it is displayed. When designing a page, it is important to plan accordingly and use css so everything is rendered in the right place relative to everything else.

[Googled Answer]

All HTML elements can be considered as boxes. In CSS, the term "box model" is used when talking about design and layout. The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content.

4. What is the difference between a div and a span?

[Your Answer]

Divs and spans both allow you to use id's or classes to apply css properties to whatever is inside their tags. The difference is that a div creates a separate line and a span allows you to apply these properties without creating a line break.

[Googled Answer]
The difference between span and div is that a span element is in-line and usually used for a small chunk of HTML inside a line (such as inside a paragraph) whereas a div (division) element is block-line (which is basically equivalent to having a line-break before and after it) and used to group larger chunks of code.

5. What is "Semantic HTML"? Try to explain this concept and give 4 examples of semantic html tags.

[Your Answer]
Semantic HTML elements do not do anything by themselves. They are containers for ID's and classes that allow you to apply css properties to whatever is inside of them. Functionally, they work the same as div's. However, semantic HTML elements are more descriptive in terms of labeling specific parts of the page allowing for easy reading by people, browsers or search engines looking at your code.
Four examples:
<header>, <footer>, <aside>, <section>/

[Googled Answer]
Semantic HTML is the use of HTML markup to reinforce the semantics, or meaning, of the information in webpages and web applications rather than merely to define its presentation or look. Semantic HTML is processed by traditional web browsers as well as by many other user agents. CSS is used to suggest its presentation to human users.

6. The steps to pushing changes to a new git repo are laid out below - but they are out of order. Put them in the correct order. Feel free to try it out on your computer to confirm that you are right.
Run "atom ." in the terminal and start working on the project
Run the command "git add ."
Run the command "git commit -m "initial commit"
Create a new repo on your github account  Set the remote the remote branch on your local project
Push to the new remote repo

7. What is the "front-end"? What are some skills that would be important for front end developers to master? (You can list both hard and soft skills)
The front-end is focused on how webpages look and how users can directly interact with them. Front-end developers should be skilled at visual design, HTML, CSS, JavaScript, an ability to make sure a page will be displayed correctly on different screen sizes, and an ability to make code streamlined so pages load quickly and without demanding too many resources.

8. Fill in the css below to make the box have a 3px blue border, with text aligned to the center, and a background color of #eee.

<div class="box">
    ....
</div>

<style>
.box {
  border-width: 3px;
  border-color: blue;
  text-align: center;
  background-color: #eee;
}
</style>

9. Write four Terminal commands.
cd
mkdir
touch
ls

10. What is your opinion of pair programming from what you've heard so far? Include some potential benefits or cons of pair programing.

Pair programming clearly is potentially a useful learning tool to promote both learning and productivity, though I do not believe I would enjoy doing it at all times.
Pro's include: it allows pairs to catch errors and problems more quickly both by having an extra set of eyes; it allows coders to apply different skill sets and expertises towards tackling a task; it creates redundancy so that if one coder leaves a project or is for some reason unable to continue working on it, there is still someone knowledgeable who is working on it; it forces people to talk through their thought process to promote clearity; it allows for ease of training someone new to a project by allowing them to work directly with and pick up knowledge form someone more experienced.
Con's include: Some people work at different paces and may feel rushed or slowed down by working with someone who works at a different pace; disagreements in goals, methods or implementation can slow a project down or otherwise be counterproductive if not managed appropriately.

11. Javascript is a dynamically typed language - what does this mean?

// your answer
This means that when you create a variable, you don't have to declare what data type it will hold, you can simply define it (or redefine it) as anything you want.

// googled answer
You don't have to specify the data type of a variable when you declare it, and data types are converted automatically as needed during script execution. Because JavaScript is dynamically typed, this assignment does not cause an error message.

12. First, name 4 of the primitive data types in Javascript, then, write which javascript data type is not a primitive and why/what this means.
4 primitive data types: numbers, strings, booleans, undefined.
Objects are not a primitive data type because they have can have functions built in known as methods.

13. In your own words, try to explain what a variable is.

A variable is a container for some data. By declaring the variable you put the designated data into the container.  You use the data by calling the variable. You can replace the contents of the container with something else, or even another type of data, but the container itself doesn't change.

14. A function is provided for you below. First, alter the function so that your name would be logged out. Then, create a similar function that logs out a person's name and age.

var myname = "Andrew";

function printYourName(x){
    console.log("Hello " + x + "!");
}

printYourName(myname);

var myAge = 30;

function nameAndAge(name, age){
  console.log("Your name is " + name + " and you are " + age + " years old.");
}

nameAndAge(myname, myAge);
