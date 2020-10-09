# Object-Oriented-Terminology

## Encapsulation
Encapsulation is where you ensure sensitive data is hidden from the user by declaring class variables as private and creating public get&set methods that can access / update the private variables without security concerns.

Advantages to using **Encapsulation**:
* Sensitive data is hidden from users
* Data can still be accessed / updated without interfering with the variables directly
## Abstraction
Abstraction allows you to show only the esseential attributes and hide unecessary information. The main purpose of abstraction is hiding unecessary details from users. 

Advantages to using **Abstraction**:
* The main benefit of using an abstract class is that it allows you to group several related classes as siblings.
* Abstraction helps to reduce the complexity of the design and implementation process of software.
## Polymorphism
Polymorphism refers to having methods with the same name and parameter types exhibit different behaviour depending on the receiver, allowing you to send the same message to two different objects and have them respond in different ways.

Advantages to using **Polymorphism**:
* Allows overloading (allowing two methods to have the same name but different parameters types)
* Allows the use of words and names to mean different different things in different contexts

## Inheritance
Inheritance is where you define a new class / object and have it inherit characteristics from a parent class avoiding code being rewritten. An example of this would be, Having a parent class called 'Vehicle' and a child class called 'Car' or 'Truck', inheriting characteristics such as fuel type etc. Multiple Inheritance allows the parent class to have as many child classes as you'd need.

Advantages to using **Inheritance**:
* Allows you to re-use already written code, rather than having to re-write objects
* Gives you a more organised design approach to classes and object-orientation

## Aggregation
Aggregation is where you have objects that are made up of other objects

Advantages to using **Aggretation**:
* Composition: allows you to reuse code for e.g. A Car is composed of Wheels, a Chassis and an Engine
* Collection: allows your object to contain other objects for e.g. a List contains several Items; A Set several Members.
