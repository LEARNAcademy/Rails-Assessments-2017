### Rails Course Assessment

## Week 6 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.


#### 1. There is a table called "squirrels". What SQL code would we write to print everything in the table?

SELECT * FROM squirrels;

#### 2. What is a foreign key? Where would you use it in a has many/belongs to relationship?

[Your Answer] A foreign key is the reference you make from another table, where the data can join. Working with "User" and "Resources" tables for example which have a has many/belongs to relationship, you could make a column in the "Resources" table with a foreign key of "user_id".

[Googled Answer] A FOREIGN KEY is a key used to link two tables together. A FOREIGN KEY is a field (or collection of fields) in one table that refers to the PRIMARY KEY in another table. The table containing the foreign key is called the child table, and the table containing the candidate key is called the referenced or parent table.

#### 3. There is a model called "Person". What ActiveRecord code would we write to find the Person whose name is Alice?

Person.find_by_name('Alice')
Person.where(name: 'Alice')

#### 4. What is a primary key?

It is a unique identifier given to each record.

#### 5. Describe what a join is and when you might use one.

A Join is a SQL command used when you want to query and get information from two or more tables by making a relationship between them and joining them where they have information in common such as ID, names, codes, etc.

#### 6. What does running "rake" or "rails" do?

//Your Answer This is a Rails command which runs the test suites of your app. "rails" and "rake" are mostly interchangeable commands and they can be combined with more keywords to run other processes, such as rails s to run the server, rails c to run the console, or rake routes to get all the routes of the app.

//Googled Answer Rake is a tool you can use with Ruby projects. It allows you to use ruby code to define "tasks" that can be run in the command line. Rake can be downloaded and included in ruby projects as a ruby gem. Once installed, you define tasks in a file named "Rakefile" that you add to your project. We call it a "build tool" because Rake comes with some libraries that make it easy to do tasks that are common during the build/deploy process, like file operations (creating, deleting, renaming, & moving files), publishing sites via FTP/SSH, and running tests.

#### 7. Under what circumstances do you need to create a rails migration file?

After you make changes to your database, a migration file is created which then you need to run with rails db:migrate in order to apply the changes to the database.

#### 8. Write the Postgres commands to create a database with a table (you can name your database and tables anything you want).

psql postgres;
CREATE DATABASE app-db;
\c app-db;
CREATE TABLE users (id serial PRIMARY KEY, name varchar, age integer, is_a_developer boolean);

#### 9. Give a use of an Active Record validation helpers.

You use validations to make sure that valid data is saved into the database. So for example, writing in your model "validates :property, presence :true" will only create an instance of a class if a value for the property is entered.

#### 10. What is ActiveRecord?

//Your Answer ActiveRecord is what connects the Ruby code with our SQL code. It allows us to treat databases as classes and each row as instances of these classes. We use it to interact with our database, query it and modify data.

//Googled Answer ActiveRecord is a Ruby library for working with Relational SQL Databases like MySQL and Postgres. It provides an Object Relational Mapping (ORM) with these core features:
-a single Ruby object maps to a database table
-columns are accessed by methods, and are inferred from the database schema
-methods for create, read, update, and delete (CRUD) are defined
-a DSL for easily constructing SQL queries in Ruby
