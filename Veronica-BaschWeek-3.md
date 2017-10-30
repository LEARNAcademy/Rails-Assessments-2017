### Rails Course Assessment

## Week 3 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.


#### 1. What was your impression of the mob programmimg day? Did you notice any pros or cons of this strategy?
Mob programming teaches you a lot about how you work with others, such as how outspoken or shy you are, how you express your ideas when you are confident vs. when you are not, and how you respond to the ideas of others. In a class setting such as ours, it also teaches you who you work with well and vice versa.

#### 2. What is jQuery and what are the two ways you can add it to your project?
[Your Answer]
JQuery is an easy way to make a website iteractive. The jQuery script goes in the head of an html file like this:
<script src = "my_file.js" </script>
In the jQuery file, you have to add this:
(document).ready(function() {
  alert ("doc is ready"):

  })

[Googled Answer]
jQuery is a lightweight, "write less, do more", JavaScript library.

The purpose of jQuery is to make it much easier to use JavaScript on your website.
There are several ways to start using jQuery on your web site. You can:

Download the jQuery library from jQuery.com
Include jQuery from a CDN, like Google

#### 3. Write an example of the jQuery function used to make sure the webpage has loaded before trying to load any Javascript.

(document).ready(function() {
  alert ("doc is ready"):

  })

#### 4. In a project, what piece do the HTML and CSS form (think MVC roles)? Explain a little bit about this piece or "layer".

//Your Answer

CSS would be the view because it presents the html parts to the viewer in the way that you specify. The HTML is part of the model because it creates the parts to be designed. But, it can also be part of the view because you can control parts of the code, if you wish, to be displayed a certain way to the viewer.

//Googled Answer

At a very basic level, HTML (Model) provides the very basic functionalities to other components, such as page elements or DOM structure. The role of CSS (View) is to render the page according to the structure provided and, in turn, to the actions triggered by JavaScript


#### 5. We learned that JQuery is a javascript library. What do you think a library is? Is it different than a framework? Do 5-10 min of googling to find these anwers.

I think of a framework as a structure that shows how to present something. It is like a template. A library, on the other hand, would be is more complete. I read that it is more like an entire toolkit that offers a ton of tools and things to work with to further simplify the coding experience. Another source said that a JS library is a library of pre-written JS which allows for easier development of JS-based applications.

#### 6. What are wireframes? Explain when and why you might use them.

//Your Answer
Allows you to provide a skeleton of your design as well as figure out a hierarchy for your design


//Googled Answer
A website wireframe, also known as a page schematic or screen blueprint, is a visual guide that represents the skeletal framework of a website. Wireframes are created for the purpose of arranging elements to best accomplish a particular purpose.

#### 7. What do we call the code layer that makes it possible for the user to interact with the application?

//Your Answer
I wasn't sure

//Googled Answer
In today's distributed applications, the code that manages this user interaction is in the presentation layer.

#### 8. Write two valid JQuery commands that use any two of these: .click(), .append(), .prepend(), .hide(), .show(), .toggle(), .remove()
Might look similar to this example:

```js
$(document).ready(function(){
  $( "p" ).parent( ".highlighted" ).css( "background", "red" );
});

```
1) $(this).prev().last();

2) $("button").on("click", function() P{
  $(this).hide();
  })

#### 9. What do we call the code layer responsible for handling and storing the data and logic?

//Your Answer
I wasn't sure about this one either

//Googled Answer

The data link layer provides error-free transfer of data frames from one node to another over the physical layer, allowing layers above it to assume virtually error-free transmission over the link.


#### 10. How can you traverse up and down the DOM? Give an example of two commands.

//Your Answer

You can use the parent or child to traverse. For example, .parent() traverses to the immediate parent of a tag.
$("span").parent()
or
$("span").children()

//Googled Answer

jQuery traversing, which means "move through", are used to "find" (or select) HTML elements based on their relation to other elements. Start with one selection and move through that selection until you reach the elements you desire.

Three useful jQuery methods for traversing up the DOM tree are:

parent()
parents()
parentsUntil()
