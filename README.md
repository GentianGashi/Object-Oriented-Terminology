# Object-Oriented-Terminology

## Encapsulation
Say we have a program. It has a few logically different objects which communicate with each other — according to the rules defined in the program.
Encapsulation is achieved when each object keeps its state private, inside a class. Other objects don’t have direct access to this state. Instead, they can only call a list of public functions — called methods.
So, the object manages its own state via methods — and no other class can touch it unless explicitly allowed. If you want to communicate with the object, you should use the methods provided. But (by default), you can’t change the state.

Advantages to using **Encapsulation**:
* Sensitive data is hidden from users
* Data can still be accessed / updated using a middleman (public methods) without interfering with the variables directly

## Abstraction
Abstraction can be thought of as a natural extension of encapsulation.
In object-oriented design, programs are often extremely large. And separate objects communicate with each other a lot. So maintaining a large codebase like this for years — with changes along the way — is difficult.
Abstraction is a concept aiming to ease this problem.
Applying abstraction means that each object should only expose a high-level mechanism for using it.
This mechanism should hide internal implementation details. It should only reveal operations relevant for the other objects.
Think — a coffee machine. It does a lot of stuff and makes quirky noises under the hood. But all you have to do is put in coffee and press a button.
Preferably, this mechanism should be easy to use and should rarely change over time. Think of it as a small set of public methods which any other class can call without “knowing” how they work.

Advantages to using **Abstraction**:
* The main benefit of using an abstract class is that it allows you to group several related classes as siblings.
* Abstraction helps to reduce the complexity of the design and implementation process of software.

## Polymorphism
Polymorphism means “many shapes” in Greek.

Say we have a parent class and a few child classes which inherit from it. Sometimes we want to use a collection — for example a list — which contains a mix of all these classes. Or we have a method implemented for the parent class — but we’d like to use it for the children, too.
This can be solved by using polymorphism.
Simply put, polymorphism gives a way to use a class exactly like its parent so there’s no confusion with mixing types. But each child class keeps its own methods as they are.
This typically happens by defining a (parent) interface to be reused. It outlines a bunch of common methods. Then, each child class implements its own version of these methods.
Any time a collection (such as a list) or a method expects an instance of the parent (where common methods are outlined), the language takes care of evaluating the right implementation of the common method — regardless of which child is passed.

Advantages to using **Polymorphism**:
* Allows overloading: (allowing two methods to have the same name but different parameters types)
* Allows the use of words and names to mean different things in different contexts

## Inheritance
Objects are often very similar. They share common logic. But they’re not entirely the same.
So how do we reuse the common logic and extract the unique logic into a separate class? One way to achieve this is inheritance.
It means that you create a (child) class by deriving from another (parent) class. This way, we form a hierarchy.
The child class reuses all fields and methods of the parent class (common part) and can implement its own (unique part).

Advantages to using **Inheritance**:
* Allows you to reuse code that share common logic between classes
* Reduces complexity and increasing readibility, giving you a more organised design approach to OOP

# References
* [FreeCodeCamp](https://www.freecodecamp.org/news/object-oriented-programming-concepts-21bb035f7260/)
* [University of Minnesota Deluth](https://www.d.umn.edu/~gshute/softeng/object-oriented.html)
* [University of North Florida](https://www.unf.edu/~broggio/cop3540/OOPTerms.htm)
* [Deborah's Developer MindScape](https://blogs.msmvps.com/deborahk/object-oriented-programming-oop-terms/)
