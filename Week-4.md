### Rails Course Assessment

## Week 4 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.


#### 1. What is a method in Ruby and how are they different or similar to functions in JavaScript?
A method is a function that is built into a class. Objects of that class then have access to that function. They operate similarly to functions in JavaScript in that if a function is defined within a limited scope, that function can then only be called within that scope. Some methods are built into Ruby and are usable at all times. Unlike in JavaScript, these methods are not, strictly speaking, global. Instead, these methods generally belong to the class "Class," and all other classes inherit from "Class." You can see what classes a method has access to by calling .methods on that class.

#### 2.What does it mean that a class inherits from another class? Try to explain Ruby inheritance.


[Your Answer]
If I define class Outer,
and then define class Inner < Outer
Inner is a child class of Outer and by default will inherit all of Outer's methods. This means that if Outer has a method Outer.a_method, I can also call a_method on Inner class as well without defining it in Inner. If Outer is a child class of the Most-Outer class, Inner also inherits and has access to Most-Outer's methods.

If the Inner class has an initialize method, this will cause it to override this default behavior and not inherit methods from Outer, unless I specify methods to be inherited using super.

[Googled Answer]
Inheritance is a relation between two classes. We know that all cats are mammals, and all mammals are animals. The benefit of inheritance is that classes lower down the hierarchy get the features of those higher up, but can also add specific features of their own. If all mammals breathe, then all cats breathe. In Ruby, a class can only inherit from a single other class. Some other languages support multiple inheritance, a feature that allows classes to inherit features from multiple classes, but Ruby doesn't support this.

#### 3. Look at this horrible code, and then fix it to be good ruby code.

``` ruby
class Example
  def initialize(day)
    @day=day
  end

  def day
    @day
  end

  def say_hi
    if day == "Friday"
      "TGIF!"
    elsif day == "Monday"
      "It's Monday again."
    else
      "Another day."
    end
  end
end
```


#### 4. What is rspec and what is the process for writing basic tests in RSpec?

//Your Answer
RSpec is a framework for testing Ruby code and making sure it does what it is supposed to (an example of Behavior-Driven Development). The process is to write the tests in the RSpec file before you write the code in your main file, and then refer to the tests when writing the code to make sure it passes the tests. For instance, you may write tests that create objects and then make sure they behave the way you want them to. Then you would write Ruby code defining the classes that these test objects will belong to.

When you are first writing an RSpec test, it is for a limited portion of code, with the expectation that the test will initially fail. You write a "describe" block in English how you expect the code to behave, and then you write an "it" block with how the code should actually behave. You can then change your Ruby code to make it pass that test. Then you write a failing test for the next portion of the code you intend to write, and continue incrementally.

//Googled Answer
To understand why RSpec is the way it is, we need to understand the point of BDD and its parent, TDD.

The idea of test-driven development (TDD) was first brought to a wider audience by Kent Beck in his 2000 book Extreme Programming Explained. Instead of always writing tests for some code we already have, we work in a red-green loop:

Write the smallest possible test case that matches what we need to program.
Run the test and watch it fail. This gets you into thinking how to write only the code that makes it pass.
Write some code with the goal of making the test pass.
Run your test suite. Repeat steps 3 and 4 until all tests pass.
Go back and refactor your new code, making it as simple and clear as possible while keeping the test suite green.This workflow implies a "step zero": taking time to think carefully about what exactly it is we need to build, and how. When we always start with the implementation, it is easy to lose focus, write unnecessary code, and get stuck.

Behavior-driven development is a concept built on top of TDD. The idea is to write tests as specifications of system behavior. It is about a different way of approaching the same challenge, which leads us to think more clearly and write tests that are easier to understand and maintain. This in turn helps us write better implementation code.


#### 5. Use Ruby to loop over this array, multiplying each element by 2.(You can try it out in irb first to test your solution)

``` ruby
tempArray = [1, 2, 6, 9, 3, 21]
tempArray.each do |el|
p el * 2
end
```

#### 6. From all the built in Ruby methods we've seen in class this week, choose three that you think are particularly helpful and create examples to show each of them below. (wrap your code in three backticks ``` code ``` to have it be read as code)

//Your Answer
1) .to_i allows you to take a number that is in the form of a string (such as one entered by a user) and do mathematical evaluations on it. This is useful because when you "get" any kind of text input from a user, it will be in the format of a string. .to_i can turn that string into something that Ruby recognizes as a number.
Example:
```ruby
num = "6"
num = num.to_i
double = (num * 2)
p double #will return 12
```
2) .superclass lets you see what a class's parent class is. This is useful because if you have a class and call the .class method on it, it will return "Class," which is probably not very helpful. .superclass actually lets you see the class a given class inherits directly from.

```ruby

class Mammal
end
class Cat < Animal
end
waffles = Cat.new
waffles.class #returns Cat
waffles.class.class #returns Class
waffles.class.superclass #returns Mammal
```

3) .new. While it is very basic, I think it is useful to think of .new as a method of class, because it helps get one into a mode of object-oriented thinking: all methods, even the really basic ones, belong to some class rather than being global.

```ruby
class Dog
fido = Dog.new
```
//Googled Answer
1) <=>
The spaceship—or sort—operator. It appears in most of the built-in Ruby classes, and is useful when working with enumerables. To illustrate how it works, let’s look at how it behaves for Fixnums. If you call 5<=>5, it returns 0. If you call 4<=>5, it returns -1. If you call 5<=>4, it returns 1. Basically, if the two numbers are the same, it returns 0, otherwise it returns -1 for least to greatest sorting and 1 for reverse sorting. You can use the spaceship in your own classes by including the comparable module and redefining <=> with logic branching to make it return -1, 0, and 1 for the cases you want.

2) .sort
[5, 1, 3].sort returns another array, with the elements sorted: [1, 3, 5].

3) It's common knowledge that Array#*, when supplied with a number, multiplies the size of the array by using duplicate elements:

[1, 2, 3] * 3 == [1, 2, 3, 1, 2, 3, 1, 2, 3]
It's not well known, however, that when given a string as an argument Array#* does a join!

%w{this is a test} * ", "                 # => "this, is, a, test"
h = { :name => "Fred", :age => 77 }
h.map { |i| i * "=" } * "n"              # => "age=77nname=Fred"

#### 7. Name three possible relationships between ruby objects?

//Your Answer

has_one
has_many
belongs_to

//Googled Answer

has_and_belongs_to_many
has_one :through
belongs_to :through

#### 8. What do we call the #{} convention used below? What is it accomplishing?

```ruby
x = 1022
puts "I am printing a random number #{x}"
```

This is string interpolation. It is a quick way to put the Ruby variable X into a string. You can also use concatenation like you would in JavaScript but it is more cumbersome.

#### 9. How do you feel about testing right now? What potential pros/cons/barriers/advantages do you see to implementing BDD in your own code?

//Your Answer
So far I like it because it makes you break a task into manageable chunks so you can work on just one thing at a time and not get overwhelmed. It helps you keep from getting off-track by guiding you as to exactly what you're going to write before you have to go back and consider exactly what you want to accomplish before you write the next set of tests. It also lets helps you figure out later what the code you (or someone else wrote) does and makes it easier to avoid breaking something. For me the main disadvantage is having two files, a main file and a testing file, means it's twice as likely to make some kind of syntax error.

//Googled Answer
Advantage: You'll know when you're done with a feature and when to call a story "done" as far as code complete and know you've satisfied the business requirements. You will be guided right from the beginning on where to start with your test driving of your code for a new feature. When you run your tests, they'll most likely be segregated nicely by use case thus telling you a story on what each set of tests are testing.

Disadavantage:  Because communications between the user and the developer are essential, if the user if not available, it will be difficult to work past ambiguities and questions generated by the user stories.

#### 10. What is an instance variable in Ruby? How is it different from a normal, local variable?

//Your Answer
If I have an instance variable defined in a method, every other method within that scope can access that variable. In addition, every object of the class in which the variable is defined can have its own version of that variable. By contrast, if you define a regular variable inside of a method, the scope of the variable is only inside that method and you can't use it anywhere else, even inside the same object.

//Googled Answer
A local variable can be used only within the method in which it is defined (or, when the variable is defined at the top level, only outside of any method). An instance variable can be used from any method that is called on the same instance.
