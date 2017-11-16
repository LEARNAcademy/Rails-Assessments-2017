### Rails Course Assessment

## Week 6 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.


#### 1. There is a table called "squirrels". What SQL code would we write to print everything in the table?
SELECT * FROM squirrels;

#### 2. What is a foreign key? Where would you use it in a has many/belongs to relationship?


[Your Answer]
A foreign key in a table is a column that references another table, often as a numeric ID, which allows you to store data in the second table which is relevant to the first table. If table 1 has_many instances of table 2 rows, (meaning each table 2 entry belongs_to a table 1 entry), you might have a foreign key in table 2 - you could add a column with the following SQL command: ALTER TABLE table_2 ADD table_1_id integer REFERENCES table_1(id). This would allow you to find multiple entries in table 2 that all correspond to a single entry in table 1. The table_1_id value in table 2 would correspond to the primary key of the table 1 entry that it belongs_to.

[Googled Answer]
A foreign key is a key used to link two tables together. This is sometimes also called as a referencing key. A Foreign Key is a column or a combination of columns whose values match a Primary Key in a different table. The relationship between 2 tables matches the Primary Key in one of the tables with a Foreign Key in the second table. If a table has a primary key defined on any field(s), then you cannot have two records having the same value of that field(s).

#### 3. There is a model called "Person". What ActiveRecord code would we write to find the Person whose name is Alice?
Person.where(name: "Alice")

#### 4. What is a primary key?
A unique identifier of each item in a table. This is usually an integer that increments for each table item.

#### 5. Describe what a join is and when you might use one.
A join lets you combine entries from two tables in SQL. You would use one if each table has a column with values that are identical to each other, possibly through a foreign key.

#### 6. What does running "rake" or "rails" do?

//Your Answer
On the command line, running "rake" by itself will run all of the test files in the spec folder in your rails project. Besides that "rake" or "rails" (which as of the latest version of Rails can mostly be used interchangeably) can be the beginning of a number of commands on the command line such as "rails generate"/"rake generate" to create files, "rails c"/"rake c" to run Ruby/ActiveRecord in the console, or "rails s"/"rake s" to start running the server.

//Googled Answer
Rake is Ruby Make, a standalone Ruby utility that replaces the Unix utility 'make', and uses a 'Rakefile' and .rake files to build up a list of tasks. In Rails, Rake is used for common administration tasks, especially sophisticated ones that build off of each other. You can get a list of Rake tasks available to you, which will often depend on your current directory, by typing rake --tasks. Each task has a description, and should help you find the thing you need.

#### 7. Under what circumstances do you need to create a rails migration file?
Migration files are used for creating, modifying or destroying tables. Once you create the files and run rake:db migrate it will save the changes in your schema file.

#### 8. Write the Postgres commands to create a database with a table (you can name your database and tables anything you want).
CREATE DATABASE plants;
\c plants;
CREATE TABLE trees (id serial PRIMARY KEY, species varchar, maximum_height integer, extinct boolean);
#### 9. Give a use of an Active Record validation helpers.
Using the table from the previous answer, the command:
Tree.create(:species => "Sequoia").valid?
...would return true as the entry is a valid datatype (string) for that column.

#### 10. What is ActiveRecord?

//Your Answer
ActiveRecord is the means of interacting with databases that is used with Rails. It allows you to manipulate tables using Ruby code. It treats a table as a class, a row as an object, and a column as a method.

//Googled Answer
Rails Active Records provide an interface and binding between the tables in a relational database and the Ruby program code that manipulates database records. Ruby method names are automatically generated from the field names of database tables. Each Active Record object has CRUD (Create, Read, Update, and Delete) methods for database access. This strategy allows simple designs and straight forward mappings between database tables and application objects.
