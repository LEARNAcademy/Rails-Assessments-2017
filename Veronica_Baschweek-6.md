### Rails Course Assessment

## Week 6 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.


#### 1. There is a table called "squirrels". What SQL code would we write to print everything in the table?

SELECT * FROM squirrels

#### 2. What is a foreign key? Where would you use it in a has many/belongs to relationship?

[Your Answer]

The foreign key is a key that links two tables together. If you have two tables, table1 can link to table2 with a foreign key/primary key. Table1 could have the primary key, which we can call "unique_id", and so table2, in order to link up info between the two tables, must have a foreign key also named "unique_id", which takes the same unique_id from table1.
If table1 has other tables in addition to table2 that need to be linked to it, that's where "has_many" and "belongs_to" comes in. Table2, and all the other tables, will have a "belongs_to" association with table1, which has a "has_many" relationship with its other tables. The other tables will also have matching foreign keys that correspond to table1's primary key.

[Googled Answer]

If you don't know what a foreign key is, well, quite simply, a foreign key links one table to another's primary key. For example, if I have an authors table and a books table, I could create a foreign key that points from books back to authors, thereby linking the two tables together. Then, these two tables become linked. This means that I cannot add or update the record with invalid data for the author_id field in the books table.

#### 3. There is a model called "Person". What ActiveRecord code would we write to find the Person whose name is Alice?

SELECT * FROM Person WHERE name = Alice

#### 4. What is a primary key?
A primary key is a table's main unique id.

#### 5. Describe what a join is and when you might use one.

Join is a way to extract data from two different but related tables. For example, one table has information about art types:, year popular and country of origin. The other table has information about artists: country, medium, and type. If we want to see information about all the artists from years a specific art type was popular, we could use join to select the art type table's "year popular" and the artist's table's "country", joining them by "country", which is common to both tables, to see the artists popular in specific years.

#### 6. What does running "rake" or "rails" do?

//Your Answer

Rake or rails can create tasks and update ones that you are working on.

//Googled Answer

rake:
Rake is Ruby Make, a standalone Ruby utility that replaces the Unix utility ‘make’, and uses a ‘Rakefile’ and .rake files to build up a list of tasks. In Rails, Rake is used for common administration tasks, especially sophisticated ones that build off of each other.

rails:
Rails will set you up with what seems like a huge amount of stuff for such a tiny command! You’ve got the entire Rails directory structure now with all the code you need to run our simple application right out of the box.

The rails server command launches a small web server named WEBrick which comes bundled with Ruby. You’ll use this any time you want to access your application through a web browser.


#### 7. Under what circumstances do you need to create a rails migration file?

If you need to change or update a database, you will create a migration file so that way you can capture the changes and they can be repeated by other people instead of telling others the step by step instructions for updating the original.

#### 8. Write the Postgres commands to create a database with a table (you can name your database and tables anything you want).

CREATE TABLE awesome_person (hobbies varchar, age integer, job varchar)
CREATE DATABASE awesome_database

#### 9. Give a use of an Active Record validation helpers.

If you want to make sure something is valid, you can use a validation helper. For example, if you want to make sure that a user enters a username into a text box on a webpage, you can insert a validation code into the model like this:

validates :username, presence: true

That makes sure the user inputs a username, otherwise they get an error message.

#### 10. What is ActiveRecord?

//Your Answer

It's a way to work with databases like MySQL and Postgres. It let's you work back and forth between your database and your rails logic, intertwining the two.

//Googled Answer

ActiveRecord is a Ruby library for working with Relational SQL Databases like MySQL and Postgres. It provides an Object Relational Mapping (ORM) with these core features:
a single Ruby object maps to a database table
columns are accessed by methods, and are inferred from the database schema
methods for create, read, update, and delete (CRUD) are defined
a DSL for easily constructing SQL queries in Ruby

Active Record is the M in MVC - the model - which is the layer of the system responsible for representing business data and logic. Active Record facilitates the creation and use of business objects whose data requires persistent storage to a database.
