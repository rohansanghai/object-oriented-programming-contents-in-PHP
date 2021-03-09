# Object oriented programming contents in PHP

> Click :star: if you like the project. Pull Requests are highly appreciated.

### Table of Contents
-------------------------------------------------------------------
| No. | Questions |
|---- | ---------
|1  | [Class](#class) |
|2  | [Object](#object) |
|3  | [New](#git-staging-files)|
|4  | [Constructor](#constructor)|
|5  | [Destructor](#destructor)|
|6  | [Inheritance](#Inheritance)|
|7  | [Parent class](#parent-class) |
|8  | [Child class](#child-class) |
|9  | [Polymorphism](#polymorphism)|
|10  | [Data Abstraction](#data-abstraction)|
|11  | [Encapsulation](#encapsulation)|
|12  | [Constants](#constants)|
|13  | [Abstract Classes](#abstract-classes)|
|14  | [Static Keyword](#static-keyword)|
|15  | [Final Keyword](#final-keyword)|


1.  ### Class
    Class is the template which contains class members. class members are properties and methods.
    Property - Variable declared within the class.
    Method - Function declared within the class.
    
    **[⬆ Back to Top](#table-of-contents)**

2.  ### Object
    An object is the memory location of the class variables. We can access the class variables with the support of object.
    
    **[⬆ Back to Top](#table-of-contents)**

3.  ### New
    By using this keyword we can allocate space in the new memory locations to load class content.
    
    **[⬆ Back to Top](#table-of-contents)**

4.   ### Constructor
    The constructor is one the type of method which is having class name same as method name. 
    By default, every class contains a default constructor used to load class     constraints.
    In PHP we can use constructor in two ways -
    Using constructor keyword (default constructor) - __constructor().
    Using class name - className().
    
    **[⬆ Back to Top](#table-of-contents)**
    
5.  ### Destructor
    Destructor is the special type of method, which can be executed at the time of destroying object of class. By using __destructor() we can create destructor. In PHP, the class objects will get destroyed when execution of the script is completed. We can also destroy class object between script execution using the unset function.
    
    **[⬆ Back to Top](#table-of-contents)**

6.  ### Inheritance
    When a class is defined by inheriting the existing function of a parent class then it is called inheritance. Here child class will inherit all or a few member functions and variables of a parent class.
    
    **[⬆ Back to Top](#table-of-contents)**

7.  ### Parent class
    A class that is inherited from another class. This is also called a base class or superclass.
    
    **[⬆ Back to Top](#table-of-contents)**

8.  ### Child Class
    A class that inherits from another class. This is also called a subclass or derived class.
    
    **[⬆ Back to Top](#table-of-contents)**

9.  ### Polymorphism
    This is an object-oriented concept where the same function can be used for different purposes. For example, the function name will remain the same but it takes a different number of arguments and can do different tasks.
    
    **[⬆ Back to Top](#table-of-contents)**

10. ### Data Abstraction
    Any representation of data in which the implementation details are hidden (abstracted).
    
    **[⬆ Back to Top](#table-of-contents)**

11. ### Encapsulation
    This refers to a concept where we encapsulate all the data and member functions together to form an object.
    
    **[⬆ Back to Top](#table-of-contents)**

12. ### Constants
    A constant is somewhat like a variable, in that it holds a value, but is really more like a function because a constant is immutable. Once you declare a constant, it does not change.
    
    **[⬆ Back to Top](#table-of-contents)**

13. ### Abstract Classes
    An abstract class is one that cannot be instantiated, only inherited. You declare an abstract class with the keyword abstract.
    
    **[⬆ Back to Top](#table-of-contents)**

14. ### Static Keyword
    Declaring class members or methods as static makes them accessible without needing an instantiation of the class. A member declared as static can not be accessed with an instantiated class object (though a static method can).
    
    **[⬆ Back to Top](#table-of-contents)**

15. ### Final Keyword
    PHP 5 introduces the final keyword, which prevents child classes from overriding a method by prefixing the definition with final. If the class itself is being defined final then it cannot be extended.
    
    **[⬆ Back to Top](#table-of-contents)**
