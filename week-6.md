### Rails Course Assessment

## Week 6 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.


#### 1. There is a table called "squirrels". What SQL code would we write to print everything in the table?
SELECT * FROM squirrels;

#### 2. What is a foreign key? Where would you use it in a has many/belongs to relationship?


[Your Answer]
A foreign key in a table is a reference to another table, often as a numeric ID, which allows you to store data in the second table which is relevant to the first table. If table 1 has_many instances of table 2 rows, (meaning each table 2 entry belongs_to a table 1 entry), you might have a foreign key in table 2 - you could add a column with the following SQL command: ALTER TABLE table_2 ADD table_1_id integer REFERENCES table_1(id). This would allow you to find multiple entries in table 2 that all correspond to a single entry in table 1. The table_1_id value in table 2 would correspond to the primary key of the table 1 entry that it belongs_to.

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

//Googled Answer


#### 7. Under what circumstances do you need to create a rails migration file?


#### 8. Write the Postgres commands to create a database with a table (you can name your database and tables anything you want).
CREATE DATABASE plants;
\c plants;
CREATE TABLE trees (id serial PRIMARY KEY, species varchar, maximum_size integer, extinct boolean);
#### 9. Give a use of an Active Record validation helpers.


#### 10. What is ActiveRecord?

//Your Answer

//Googled Answer
