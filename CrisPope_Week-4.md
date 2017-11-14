### Rails Course Assessment

## Week 4 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.


#### 1. What is a method in Ruby and how are they different or similar to functions in JavaScript?
Methods are actions for an object and are called on objects with dot syntax. They are similar to functions in JavaScript as both are blocks of code that get executed when calling them and can have arguments.

#### 2.What does it mean that a class inherits from another class? Try to explain Ruby inheritance.

[Your Answer] Ruby inheritance means that a child class inherits the methods from all its parent classes. If a child class has a method with the same name, the one which is further down will override the parent one. 

[Googled Answer] Inheritance is a relation between two classes. The benefit of inheritance is that classes lower down the hierarchy get the features of those higher up, but can also add specific features of their own. In Ruby, a class can only inherit from a single other class. Some other languages support multiple inheritance.

#### 3. Look at this horrible code, and then fix it to be good ruby code. 

``` ruby
class Example
  def initialize(day)
    @day=day
  end
  
  def say_hi
    if day == "Friday" 
    puts "TGIF!"
    elsif day == "Monday"
      puts "It's monday again"
    else
      puts "another day"
    end
  end
end
```

#### 4. What is rspec and what is the process for writing basic tests in RSpec?

//Your Answer Rspec is a testing tool used to test Ruby code during Behavior Driven Development. It is one of the gems we can install that comes with Ruby. To write a basic test in Rspec: 
-make a file with ruby code - .rb
-make a test file - _spec.rb
-in the spec file you need to require rspec and the name of the file to test 
-write the test first so it fails
-check the test by running it in the console `rspec testfile_spec.rb'`
-write only the ruby code for that test to pass
-check the test passes in the console
-write the next test to fail and so on

//Googled Answer RSpec is a 'Domain Specific Language' (DSL) testing tool written in Ruby to test Ruby code. It is a behavior-driven development (BDD) framework which is extensively used in the production applications. The basic idea behind this concept is that of Test Driven Development(TDD) where the tests are written first and the development is based on writing just enough code that will fulfill those tests followed by refactoring.

#### 5. Use Ruby to loop over this array, multiplying each element by 2.(You can try it out in irb first to test your solution)

tempArray = [1, 2, 6, 9, 3, 21]

```ruby
tempArray.each do |x|
  puts x * 2
end

for x in tempArray 
  puts x * 2
end
```

#### 6. From all the built in Ruby methods we've seen in class this week, choose three that you think are particularly helpful and create examples to show each of them below. (wrap your code in three backticks ``` code ``` to have it be read as code)

//Your Answer

```ruby
array = [2, 1, 3, "Cris"]

#include method
array.include?(3) #returns true

#shovel 
array << "Ruby" 
array #returns [2, 1, 3, "Cris", "Ruby"] which is modified

#reverse
array.reverse #returns ["Ruby", "Cris", 3, 1, 2]
```

#### 7. Name three possible relationships between ruby objects? 

//Your Answer has_many, has_one, belongs_to

//Googled Answer 
Rails supports six types of associations:
belongs_to
has_one
has_many
has_many :through
has_one :through
has_and_belongs_to_many


#### 8. What do we call the #{} convention used below? What is it accomplishing?

```ruby
x = 1022
puts "I am printing a random number #{x}"
```

This is string interpolation. It is putting the value of x in the string so it prints "I am printing a random number 1022"

#### 9. How do you feel about testing right now? What potential pros/cons/barriers/advantages do you see to implementing BDD in your own code?

//Your Answer I enjoy testing. I need to remember that the testing script is running the code and taking actions while it checks. Pros: The resulting code is tested to pass so we can have more confidence that the code is effective. Cons: It makes development slower as tests need to be written before developing each piece. Barriers: Each tool uses it's own DSL which you have to learn. You are also constricted to the DSL's specific commands.  

//Googled Answer Behavior-driven development is a software development method that focuses on creating tests using concrete, real-life examples. These examples use natural language constructs (English-like sentences) to express the behavior and the expected outcomes.

Pros: It’s especially helpful when you’re working with a cross-functional team. BBD keeps the focus on the end user and their needs. Another great thing about BBD is that documentation is built in. By writing a high-level list of specifications, you’ll provide a description of what your application actually does in simple terms that every member of your team can understand. Also, both BDD and test-driven development (TDD) allow you to refactor code really well. Having comprehensive test coverage enables you to edit things very efficiently without having to worry about what breaks. Your tests will tell you what breaks right away. 

Cons: Many companies are founded by engineers who had a cool idea and put something together. And a lot of times, extensive testing isn’t a part of that. There are conflicting schools of thought on the best way to implement testing, even within a single organization.

#### 10. What is an instance variable in Ruby? How is it different from a normal, local variable?

//Your Answer Instance variables are available to a class but each object instance will have their own value. They are available between methods. A local variable is just available to the method it is declared in (like a counter in a loop).

//Googled Answer When using variables inside classes, only instance variables, which are prefixed with the `@` character, will be visible to all of the methods in the class. A variable that only exists inside of a code block or method is called a local variable. The whole concept is called scope.

