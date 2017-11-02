### Rails Course Assessment

## Week 3 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.


#### 1. What was your impression of the mob programmimg day? Did you notice any pros or cons of this strategy?

The mob programming day was interesting. I appreciate that LEARN is exposing us to different strategies for collaboration so we know what to expect. Pros: We could work faster through issues since there were more of us thinking about solutions. Makes us all be engaged and focused on the task increasing productivity. Cons: It was harder to agree on ideas and on the code itself. You get less time driving and it's more difficult to think about the solutions you might have since everything is more fast paced. 

#### 2. What is jQuery and what are the two ways you can add it to your project?

[Your Answer] jQuery is a JavaScript library which allows us to interact with HTML and make dynamic changes to websites. Adding it to your project: 1. You add the jQuery CDN link to the HTML document. 2. You download the jQuery file from the website and save it locally, then link it to the HTML. In both cases you put them inside a `<script>` tag and then write the jQuery code in a .js file (also linked to the HTML).

[Googled Answer] jQuery is a fast, small, and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, animation, and Ajax much simpler with an easy-to-use API that works across a multitude of browsers.

There are several ways to start using jQuery on your web site. You can:
-Download the jQuery library from jQuery.com
-Include jQuery from a CDN, like Google

#### 3. Write an example of the jQuery function used to make sure the webpage has loaded before trying to load any Javascript.

```js
$(document).ready(function(){


});
```
#### 4. In a project, what piece do the HTML and CSS form (think MVC roles)? Explain a little bit about this piece or "layer". 

//Your Answer HTML and CSS are the view part of the MVC. They are what is visible to the user and what the user can interact with. 

//Googled Answer  The “View” is what is presented to the User. This is usually HTML, CSS and Javascript. 

A View is a collection of classes representing the elements in the user interface (all of the things the user can see and respond to on the screen, such as buttons, display boxes, and so forth). Usually there are many (possibly nested) Views in a single application. A view can query the model, but it is not supposed to change the state. 

#### 5. We learned that JQuery is a javascript library. What do you think a library is? Is it different than a framework? Do 5-10 min of googling to find these anwers. 

A library is different from a framework. Bootstrap and jQuery are libraries. Rails, Flask and Django are frameworks. Frameworks can include libraries.

Libraries have predefined classes, methods and objects that we can call on and reuse. They usually relate to one specific area or piece of functionality. You call a library function, it executes some code and then control is returned to your code. 

A framework is a structure or skeleton of your app and comes with predefined control flow with empty spaces for the developer to fill and extend.

#### 6. What are wireframes? Explain when and why you might use them.

//Your Answer Wireframes are preliminary sketches of your project. It is the blueprint of the project that you define beforehand so you are clear of the components, features and integrations needed. It is presented to the client/team before starting the project so you can agree on the overall design, layout, functionality to make sure all parties agree on what is expected and feasible. It can be as simple as a mockup drawing to a more profesional one created using a prototype design software.

//Googled Answer Wireframing is a way to design a website service at the structural level. A wireframe is commonly used to lay out content and functionality on a page which takes into account user needs and user journeys. Wireframes are used early in the development process to establish the basic structure of a page before visual design and content is added.

#### 7. What do we call the code layer that makes it possible for the user to interact with the application? 

//Your Answer That layer is the Controller. It lets the user interact with our model and render different views. It would be methods and functions that define the functionality of the app. 

//Googled Answer The “Controller” is what connects the “View” and the “Model”. So when a User requests something from the database, the “Controller” takes that request from the “View” and sends it to the “Model”. It’s the brains of the application, and ties together the model and the view.

#### 8. Write two valid JQuery commands that use any two of these: .click(), .append(), .prepend(), .hide(), .show(), .toggle(), .remove()
Might look similar to this example:

```js
$(document).ready(function(){
  $( "p" ).parent( ".highlighted" ).css( "background", "red" );
});

```

```js
$(document).ready(function(){
  $("#submit").on("click", (function(){
  $(".player").append(name);
  }));
}

$(document).ready(function(){
  $("button").on("click", (function(){
  $("p").hide();
  $("p").show().text("Thanks for subscribing!");
  });
}

```

#### 9. What do we call the code layer responsible for handling and storing the data and logic?

//Your Answer The model layer stores the data and accesses it through queries. There are relational databases such as SQL and no-database or no-SQL models such as MongoDB and CouchDB. 

//Googled Answer The “Model” is how the website talks to the database. Model code typically reflects real-world things. This code can hold raw data, or it will define the essential components of your app. The model manages fundamental behaviors and data of the application. It can respond to requests for information, respond to instructions to change the state of its information, and even to notify observers in event-driven systems when information changes. This could be a database, or any number of data structures or storage systems. In short, it is the data and data-management of the application.

#### 10. How can you traverse up and down the DOM? Give an example of two commands.

//Your Answer You can use a selector as a starting point and find all its children, or or all its parents or certain elements in their way. Examples:

```js
$("ol").children().addClass("skills");
$("span").parent();
```

//Googled Answer jQuery traversing, which means "move through", are used to "find" (or select) HTML elements based on their relation to other elements. Start with one selection and move through that selection until you reach the elements you desire. Examples: The parent() method returns the direct parent element of the selected element. The children() method returns all direct children of the selected element.