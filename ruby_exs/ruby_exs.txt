Create a Dog class that is initialized with a name.


Create a new instance of the Dog class.


Add a bark() instance method to the Dog class that returns "Ruff ruff".


Create an instance of the Dog class and call the bark() method.


class Person
  def initialize(name, age)
    @name = name
    @age = age
  end
end
What does the following code return?

bob = Person.new("Bob", 22)
bob.speak()


class Insect
  def initialize(age_in_days)
    @age_in_days = age_in_days
  end
end
Add an instance method to the Insect class to calculate the age_in_years.

class Dog
  def speak()
    return("woof woof")
  end
end
What does the following code return? ruby Dog.speak()

Create a Lamp class with a class method called about_me that returns the String "We brighten up people's lives".

class WaterBottle
  def initialize(size)
    @size = size
  end
end
Add a method to the WaterBottle class that returns the size of the WaterBottle and demonstrate how this method can be used.

Create a Person class that is initialized with an age and create an age=() method that can be used to update the @age instance variable. Also include an age method that returns the value of the @age instance variable. Demonstrate how the methods can be used.

Modules define methods that can be added to classes. Modules are useful for organizing code and for code that can be reused in multiple classes. Unlike classes, Modules cannot be instantiated (i.e. Modules cannot be used to create objects).

module Clueless
  def funny()
    return("AS IF?!")
  end
end

class Actress
  include Clueless
end

What does this code return?
alicia = Actress.new
alicia.funny()

module HappyHappy
  def say_something()
    return("Happy happy, joy joy")
  end
end

class Person
  include HappyHappy
end

class Alien
  include HappyHappy
end
Demonstrate that instances of the Person class and instances of the Alien class can use the say_something() method.

Create a module called MathHelper with a method multiply_by_two() that takes a number as an argument and multiplies it by two. Create a class called Homework and demonstrate how multiply_by_two() can be used.
