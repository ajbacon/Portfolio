# Object-Oriented Programming Notes

Object oriented programming is a programming model which is based on the concepts of objects. The more popular object-oriented languages are class based. A **class** is a user defined blueprint from which objects are created, they represent a defined set of properties (attributes/instance variables) and methods that are common to objects of that one type (essentially classes define what an object can do). An **object** is simply an instance of a class.

The benefits of using OOP is that problems are broken down into smaller chunks, where in general (and if following SRP) objects have a single responsibility, which:

* Makes complex problems easier to develop
* More reliable
* More maintainable
* Easier to debug
* Easier to expand
* more secure

OOP insists that the user thinks about what you expose to the outside world. Users and other objects can only interact with objects via publically defined methods hence the inner workings is kept private within the object, this concept is known as Encapsulation. In this way it is easier to modify and add more code without affecting any other code. Encapsulation is one of the 4 fundamentals of OOP, this and the other 3 are defined below. 


## Encapsulation

* Encapsulation is achieved when objects keep their state private within a class
* Other objects don’t have direct access to this state, rather they can only call on a list of public methods (or functions)
* Communication with the objects is only through the available methods


## Abstraction

* Abstraction is about expressing the intent of the class/object
* One class should not need to know the inner workings of another class to interact, just knowing the interfaces should suffice
* Hence the workings of a class are “abstracted” to just their interfaces

## Inheritance

* Objects often have similar logic, but are not exactly the same
* Inheritance is the process of sharing common logic between classes
* With inheritance a child class can “inherit” from a parent class and use its logic (and also then define methods/logic of its own)

## Encapsulation


## Useful links

[Object oriented concepts](https://www.geeksforgeeks.org/object-oriented-programming-oops-concept-in-java/)
[Explaining OOP](https://www.freecodecamp.org/news/object-oriented-programming-concepts-21bb035f7260/)