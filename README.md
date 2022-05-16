## OOP: C#, JAVA, APEX, and PYTHON

### 1. OOP (object oriented programming: python Java, Apex, C#) is about creating Data and methods to perform operations on data. 


### 2. The main advantage of oop is that OOP provides a clear structure for the program, and keep it dry (don't repeat yourself " , and makes the codes easier to maintain, modify and debug. 
***
### 3. What is the structure of object-oriented programming?
### The structure, or building blocks, of object-oriented programming include the following:
* #### Classes are user-defined data types that act as the blueprint for individual objects, attributes and methods.
* #### Objects are instances of a class created with specifically defined data. Objects can correspond to real-world objects or an abstract entity. When class is defined initially, the description is the only object that is defined.
* #### Methods are functions that are defined inside a class that describe the behaviors of an object. Each method contained in class definitions starts with a reference to an instance object. Additionally, the subroutines contained in an object are called instance methods. Programmers use methods for reusability or keeping functionality encapsulated inside one object at a time.
* #### Attributes are defined in the class template and represent the state of an object. Objects will have data stored in the attributes field. Class attributes belong to the class itself.
( https://www.techtarget.com/searchapparchitecture/definition/object-oriented-programming-OOP) 
***
### 4. What are the 4 main principles of OOP: Data abstraction, Inheritance, Encapsulation and Polymorphism
 *  #### Data Abstraction: Data abstraction is a mechanism of retrieving the essentials details without dealing with background details.
  ( https://www.salesforcetutorial.com/data-abstraction/)--Check out some " What is..." in the salesforce tutorials
 *  #### Inheritance: Inheritance is the procedure in which one class inherits the attributes and methods of another class.  The class whose properties and methods are      inherited is known as Parent class. And the class that inherits the properties from the parent class is the Child class.
 *  #### Encapsulation: a way to ensure security. Basically, it hides the data from the access of outsiders.
 #### Example from C#: 
 ```
 use the Name property to access and update the private field of the Person class:
 class Person
{
  private string name; // field
  public string Name   // property
  {
    get { return name; }
    set { name = value; }
  }
}

class Program
{
  static void Main(string[] args)
  {
    Person myObj = new Person();
    myObj.Name = "Liam";
    Console.WriteLine(myObj.Name);
  }
}
// output: Liam

```
 *  #### Polymorphism: means having many forms. In OOP it refers to the functions having the same names but carrying different functionalities.

*** 
### Relationship between a class and objects: class is the Blueprint or template of objects and objects are instances . Example of class  Car has objects of types (make)of cars (Volvo, Audi, Toyota, Tesla) and their attributes or fields ( color, make, model, year ,weight) and methods (or functions: drive and brake.

####  constructor: a class is like objects constructor, or a blueprint to create objects.
#### a special method is called a constructor that is used to initialize objects. For example model=" Santa Fe" in a method is called a constructor that sets initial value for a field. 
#### Static and public are two access identifiers .

#### Methods need to be public for objects to access. Static method can be accessed without creating an object of the class. 

#### Creating an object needs to specify the class name followed by the object name, and used the keyword new: Car toyota= new Car ();
