### Rails Course Assessment

## Week 3 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.


#### 1. What was your impression of the mob programmimg day? Did you notice any pros or cons of this strategy?\

It makes a group less likely to become stuck and become completely unable to make progress on a project since more minds are thinking about solutions. It also allows more people to think big-picture about a program at once as a relatively smaller percentage of the team will be forced to engage with the detail-oriented task of writing the code out at any given time.

A disadvantage is that more people means more opinions, and when there are disagreements within a group about how to tackle a problem, time-manage, or do any  number of things, someone is going to be unhappy when they get out-voted. More voices also may make it likely for the group to get stuck on a tangent. For instance, during our day of mob programming my group opted to spend a not-insignificant amount of time white-boarding solutions to a problem we had already solved because someone speculated that we might think of a "cleaner" way of doing something.

#### 2. What is jQuery and what are the two ways you can add it to your project?


[Your Answer]
JQuery is a library that adds additional functionality to JavaScript, including numerous ways to interact with the DOM. You can add it to your project by linking to it in HTML. This can be done one of two ways: either by linking to the web address of the JQuery CDN directly, or by downloading a JQuery .js file into your project folder and linking to that file.

[Googled Answer]
jQuery is a lightweight, "write less, do more", JavaScript library. The purpose of jQuery is to make it much easier to use JavaScript on your website. jQuery takes a lot of common tasks that require many lines of JavaScript code to accomplish, and wraps them into methods that you can call with a single line of code. There are several ways to start using jQuery on your web site. You can:
Download the jQuery library from jQuery.com
Include jQuery from a CDN, like Google

#### 3. Write an example of the jQuery function used to make sure the webpage has loaded before trying to load any Javascript.

$(document).ready(function() {
    <JavaScript goes here>
});

#### 4. In a project, what piece do the HTML and CSS form (think MVC roles)? Explain a little bit about this piece or "layer".

//Your Answer
HTML and CSS form the view. This comprises the elements that actually render on the user's screen.

//Googled Answer
A view can be any output representation of information, such as a chart or a diagram. Multiple views of the same information are possible, such as a bar chart for management and a tabular view for accountants. A view generates new output to the user based on changes in the model.

#### 5. We learned that JQuery is a javascript library. What do you think a library is? Is it different than a framework? Do 5-10 min of googling to find these anwers.

Libraries and frameworks are both pre-written code with a variety of functions. When using a library, you will write code that is organized in a particular way and call upon functions from the library to do certain things to aid with that organization. With a framework, the basic scheme of organization is already written in, and you will write code within that scheme to customize it to your particular purpose.

#### 6. What are wireframes? Explain when and why you might use them.

//Your Answer
A wireframe is a bare-bones blueprint of how a website or app will be organized which a developer may create before he or she starts actually writing the code for the project. This can be done to help developers organize themselves, or can be created on behalf of (or in collaboration with) a client to make sure that the developer and the client are on the same page about what a project will do and how it will be organized to avoid misunderstandings and the need for extra work later on to fix issues arising from the developer's expectations and the client's expectations not matching.

//Googled Answer
A website wireframe, also known as a page schematic or screen blueprint, is a visual guide that represents the skeletal framework of a website. Wireframes are created for the purpose of arranging elements to best accomplish a particular purpose. The purpose is usually being informed by a business objective and a creative idea. The wireframe depicts the page layout or arrangement of the website’s content, including interface elements and navigational systems, and how they work together. The wireframe usually lacks typographic style, color, or graphics, since the main focus lies in functionality, behavior, and priority of content. In other words, it focuses on what a screen does, not what it looks like.

#### 7. What do we call the code layer that makes it possible for the user to interact with the application?

//Your Answer
This is the controller. A JavaScript file linked by an HTML page may form this layer. It allows the website to actually do things rather than just be text, images and CSS styling. This is the part that knows how to accept user input. It passes information between the view and the model.

//Googled Answer
A controller is the link between a user and the system. It provides the user with input by arranging for relevant views to present themselves in appropriate places on the screen. It provides means for user output by presenting the user with menus or other means of giving commands and data. The controller receives such user output, translates it into the appropriate messages and pass these messages on to one or more of the views.

#### 8. Write two valid JQuery commands that use any two of these: .click(), .append(), .prepend(), .hide(), .show(), .toggle(), .remove()
Might look similar to this example:

```js
$(document).ready(function(){
  $( "p" ).parent( ".highlighted" ).css( "background", "red" );
});


$(document).ready(function(){
  $("button").on("click", function() {
       $("p").append("You have just clicked a button.");
  });
});

$(document).ready(function(){
  $("#mouse_over").on("hover", function() {
      $(this).prepend("Click me!");
      $(this).hide();
  });
});
```

#### 9. What do we call the code layer responsible for handling and storing the data and logic?

//Your Answer
This is called the model. The user does not interact with the model directly but when they interact with the other layers this may cause information to be read from or written to the model.

//Googled Answer
The model manages fundamental behaviors and data of the application. It can respond to requests for information, respond to instructions to change the state of its information, and even to notify observers in event-driven systems when information changes. This could be a database, or any number of data structures or storage systems. In short, it is the data and data-management of the application.

#### 10. How can you traverse up and down the DOM? Give an example of two commands.

//Your Answer
Traversing is how you actually find the element of the page you are going to interact with by moving through other elements that are related to it. This is often done using JQuery. For instance, parent() finds the element one level up from the previously selected one, while find() will locate descendants of the previously selected element that you filter with an identifier of some kind in the parentheses.

//Googled Answer
jQuery traversing, which means "move through", are used to "find" (or select) HTML elements based on their relation to other elements. Start with one selection and move through that selection until you reach the elements you desire.
