### Rails Course Assessment

## Week 4 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.


#### 1. What is a method in Ruby and how are they different or similar to functions in JavaScript?

A method is a way of making an object do something in Ruby. Methods in Ruby and Javascript are the same, except all functions are methods in Ruby, and in Javascript, functions are only methods when they are called on other functions.


#### 2.What does it mean that a class inherits from another class? Try to explain Ruby inheritance.


[Your Answer]

Inheritance is when a parent class gives attributes to the child class. For example, a class of fish could have children classes of specific types of fish, but certain methods will be applied to all of them.

[Googled Answer]

Inheritance is when a class inherits behavior from another class. The class that is inheriting behavior is called the subclass and the class it inherits from is called the superclass.

We use inheritance as a way to extract common behaviors from classes that share that behavior, and move it to a superclass. This lets us keep logic in one place.

#### 3. Look at this horrible code, and then fix it to be good ruby code.

``` ruby
class example
  def initialize(day)
    @day=day
  end

  def Say_hi
    if day == "Friday"
      puts "TGIF!"
    elsif day == "Monday"
      puts "Its monday again"
    else
      puts "another day"
  end
end
```


#### 4. What is rspec and what is the process for writing basic tests in RSpec?

//Your Answer

RSpec is a tool to test ruby code. It allows the test to be written in a way that describes the desired behavior of an app, focusing on the "what" rather than the "how". You start with the word "describe" followed by the object or whatever you are testing, then you say what it should do and what you expect, as in this example:
  describe "Thing" do
    it "has to be real" do
      expect {Thing.new}.to_not raise_error
    end
  end

//Googled Answer

RSpec is a testing tool for Ruby, created for behavior-driven development (BDD).

The basic structure of a test: describe.

This will be your bread and butter because it organizes your specs. You can reference strings or classes themselves.

Describe sections are the basic building blocks to organize your tests into logical, coherent groups to test. Basically, a scope for different parts of your application that you want to test.

#### 5. Use Ruby to loop over this array, multiplying each element by 2.(You can try it out in irb first to test your solution)

tempArray = [1, 2, 6, 9, 3, 21]

tempArray.each do |i|
  puts i * 2
end


#### 6. From all the built in Ruby methods we've seen in class this week, choose three that you think are particularly helpful and create examples to show each of them below. (wrap your code in three backticks ``` code ``` to have it be read as code)

//Your Answer

1)
array << 42
This is the shovel method that puts a value into an array

2)
variable.respond_to?(:method)
This one lets us know if a variable is part of a method or has an attribute associated with it.

3)
variable.to_i
This one lets a number that might be read as a string be interpreted as an integer.

//Googled Answer


#### 7. Name three possible relationships between ruby objects?

//Your Answer
I am confused about this question. All the answers I've seen pertain to rails. My best guess is that it has to do with the "has_one", "has_many", and "belongs_to" associations, but I still don't understand this.

//Googled Answer
Rails supports six types of associations:

belongs_to
has_one
has_many
has_many :through
has_one :through
has_and_belongs_to_many
Associations are implemented using macro-style calls, so that you can declaratively add features to your models. For example, by declaring that one model belongs_to another, you instruct Rails to maintain Primary Key-Foreign Key information between instances of the two models, and you also get a number of utility methods added to your model.

#### 8. What do we call the #{} convention used below? What is it accomplishing?

```ruby
x = 1022
puts "I am printing a random number #{x}"
```

This is interpolating. That allows you to put in a variable, and it will be read as the value of that variable.

#### 9. How do you feel about testing right now? What potential pros/cons/barriers/advantages do you see to implementing BDD in your own code?

//Your Answer

Testing is a bit confusing but I can definitely see some advantages when thinking long-term. It'll help you avoid problems down the road. So, even though it takes longer initially, which is annoying, it can potentially save a lot more time later on. You do have to make sure, though, that you write good and thorough tests.

//Googled Answer

Pros:
Unit testing finds problems early in the development cycle. This includes both bugs in the programmer's implementation and flaws or missing parts of the specification for the unit. The process of writing a thorough set of tests forces the author to think through inputs, outputs, and error conditions, and thus more crisply define the unit's desired behavior. The cost of finding a bug before coding begins or when the code is first written is considerably lower than the cost of detecting, identifying, and correcting the bug later; bugs may also cause problems for the end-users of the software

Cons:
Testing will not catch every error in the program, because it cannot evaluate every execution path in any but the most trivial programs. This problem is a superset of the halting problem, which is undecidable. The same is true for unit testing. Additionally, unit testing by definition only tests the functionality of the units themselves. Therefore, it will not catch integration errors or broader system-level errors (such as functions performed across multiple units, or non-functional test areas such as performance).


#### 10. What is an instance variable in Ruby? How is it different from a normal, local variable?

//Your Answer

An instance variable is only for one instance of an object. It can have a default, but if one object decides to change the value of that, it will only change that time and the default will remain until anther object decides to change it.
A local variable is defined in a method and is only associated with that method. Objects can't call it or change it outside of its method.

//Googled Answer

The normal variable is called a local variable and is local to the code construct in which it was defined (if you define it in a method it cannot be accessed outside that method).

An instance variable is local to a specific instance of an object. If one object changes the value of the instance variable, the change only occurs for that object.
