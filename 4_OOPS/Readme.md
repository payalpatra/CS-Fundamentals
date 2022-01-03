### What is OBJECT-ORIENTED PROGRAMMING?

Object-oriented programming is a programming paradigm built on the concept of objects.
In Other Words, it is an approach to problem-solving where all computations are carried out using objects.

1.  Program is divided into small parts called objects.
2.  Object-oriented programming follows a bottom-up approach.
3.  Have access specifiers like private, public, protected, etc.
4.  Adding new data and functions is easy.
5.  Provides data hiding so it is more secure than procedural programming.
6.  Overloading is possible in object-oriented programming.
7.  Data is more important than function.
8.  Provides the ability to simulate real-world
9.  Examples: C++, Java, Python, C#, JavaScript, Ruby, PHP, VB.NE

### TERMINOLOGIES

- **Class** - A class is a group of objects that share common properties and behavior.It is a blueprint or template from which objects are created. <BR/>
- **Object**- Object is any real-world entity that can have some characteristics or which can perform some tasks. It is also called the instance of a class<BR/>

For example, we can consider a car as a class that has characteristics like steering wheels, seats, brakes, etc.<BR/>
Class - color. Red - an object of color<BR/>

- **Constructor** - Constructors are special methods whose name is the same as the class name. The constructors serve the special purpose of initializing the objects.<BR/>
- **Interface** - Like a class, an interface can have methods and variables, but the methods declared in an interface are by default abstract.<BR/>
- **Default constructor** - The default constructor is the constructor which doesn’t take any argument. It has no parameters.<BR/>
- **Parameterized constructor** - The constructors that take some arguments are known as parameterized constructors.<BR/>
- **Copy constructor** - A copy constructor is a member function that initializes an object using another object of the same class.<BR/>
- **Friend Function** - It is basically a function that is used to access all private and protected members of classes.<BR/>
- **Member Function** - It is basically a function that can be declared as members of a class. It is usually declared inside the class definition and works on data members of the same class.<BR/>
- **Destructor** - It frees up the resources and memory occupied by an object. Destructors are automatically called when an object is being destroyed.<BR/>
- **Subclass** - The subclass is a part of Inheritance. The subclass is an entity, which inherits from another class. It is also known as the child class.<BR/>
- **Superclass** - Superclass is also a part of Inheritance. The superclass is an entity, which allows subclasses or child classes to inherit from itself.<BR/>
- **Abstract Class** - An abstract class is a special class containing abstract methods. The significance of abstract class is that the abstract methods inside it are not implemented and only declared. So as a result, when a subclass inherits the abstract class and needs to use its abstract methods, they need to define and implement them.<BR/>
- **Abstract Method** - An abstract method is a method that doesn’t have anybody. <BR/>
- **Methods** - A method is a procedure or function in OOPs Concepts. It is a set of instructions that are associated with an object.<BR/>
- **Static Method** - A static method is a method that belongs to a class, but it does not belong to an instance of that class and this method can be called without the instance or object of that class. Non-static methods can access any static method and static variable, without creating an instance of the object.<BR/>

- **Overloading** - Overloading is a compile-time polymorphism feature in which an entity has multiple implementations with the same name.<BR/>
- **Overriding** - Whereas Overriding is a runtime polymorphism feature in which an entity has the same name, but its implementation changes during execution.<BR/>
- **Exception** - An exception can be considered as a special event, which is raised during the execution of a program at runtime, that brings the execution to a halt.<BR/>
- **Exception handling** - It is the mechanism for identifying the undesirable states that the program can reach and specifying the desirable outcomes of such states.
  Try-catch is the most common method used for handling exceptions in the program.<BR/>
  Garbage Collection: It refers to the mechanism of handling the memory in the program. Through garbage collection, the unwanted memory is freed up by removing the objects that are no longer needed.<BR/>

- **Interface v/s Abstract class difference** - Interface and abstract classes both are special types of classes that contain only the method declaration and not their implementation. But the interface is entirely different from an abstract class. The main difference between the two is that, when an interface is implemented, the subclass must define all its methods and provide its implementation. Whereas when an abstract class is inherited, the subclass does not need to provide the definition of its abstract method, until and unless the subclass is using it.
  Also, an abstract class can contain abstract methods as well as non-abstract methods<BR/>

- **Private** - The access level of a private modifier is only within the class. It cannot be accessed from outside the class.<BR/>
- **Default** - The access level of a default modifier is only within the package. It cannot be accessed from outside the package. If you do not specify any access level, it will be the default.<BR/>
- **Protected** - The access level of a protected modifier is within the package and outside the package through child class. If you do not make the child class, it cannot be accessed from outside the package.<BR/>
- **Public** - The access level of a public modifier is everywhere. It can be accessed from within the class, outside the class, within the package and outside the package.<BR/>

* **Protected** - The access level of a protected modifier is within the package and outside the package through child class. If you do not make the child class, it cannot be accessed from outside the package.<BR/>
* **Public** - The access level of a public modifier is everywhere. It can be accessed from within the class, outside the class, within the package and outside the package.<BR/>

### What we use object-oriented programming?

Object-oriented programming is the programming paradigm that is defined using objects. Objects can be considered as real-world instances of entities like class, that have some characteristics and behaviors. <BR/>

* OOPs helps users to understand the software easily, although they don’t know the actual implementation.
* With OOPs, the readability, understandability, and maintainability of the code increases multifold.
* Even very big software can be easily written and managed easily using OOPs.


### What are the main features of OOPs?

### Data Abstraction
1. Data abstraction refers to providing only essential information about the data to the outside world, hiding the background details or implementation.
2. Hiding the implementation and displaying only the functionality to the users.

### Advantages 
1. It reduces the complexity of viewing things.
2. Reduces the duplication of the code

#### Real Life Example
Consider a real-life example of a man driving a car. The man only knows that pressing the accelerators will increase the speed of the car or applying brakes will stop the car but he does not know about how on pressing the accelerator the speed is actually increasing, he does not know about the inner mechanism of the car or the implementation of the accelerator, brakes, etc in the car.

### Encapsulation
It describes the idea of bundling data and methods that work on that data within one unit.

#### Advantages 
1. Encapsulation protects an object from unwanted access by clients. 
2. Simplifies the maintenance of the application

#### Real Life Example
A Real-Life Example of Encapsulation is a School Bag. 


### Polymorphism
The word polymorphism means having many forms. It describes the concept that different classes can be used with the same interface.
Polymorphism is the ability of any data to be processed in more than one form. <br/>

Polymorphism is divided into two types: <br/>

* **Compile Time Polymorphism** - Compile time polymorphism, also known as Static Polymorphism, refers to the type of Polymorphism that happens at compile time. What it means is that the compiler decides what shape or value has to be taken by the entity in the picture. <br/>
* **Runtime Polymorphism** - Runtime polymorphism, also known as Dynamic Polymorphism, refers to the type of Polymorphism that happens at the run time. What it means is it can't be decided by the compiler. Therefore what shape or value has to be taken depends upon the execution. Hence the name Runtime Polymorphism.

#### Advantages 

1. It helps the programmer to reuse the codes, i.e. classes once written, tested and implemented can be reused as required. Saves a lot of time.
2. A single variable can be used to store multiple data types.

#### Real Life Example
Like a man at the same time is a father, a husband, an employee. So the same person possesses different behavior in different situations. This is called polymorphism.


### Inheritance
 Inheritance is a feature of OOPs which allows subclasses classes to inherit properties from the parent class. <BR/>
 
 Types of Inheritance
 
* **Single inheritance** - When a class inherits from a single class, it is known as a single inheritance
* **Multiple inheritances** - Multiple inheritances come into the picture when a class inherits from more than one base class. Parent 1 && Parent2 → child
* **Multilevel inheritance** - When there is a chain of inheritance, it is known as multilevel inheritance. Example: Animal →  Dog → Puppy
Puppy Inherits from the Dog Class, Dog class inherits from the Class Animal. 
 
* **Hierarchical inheritance** - When two or more classes inherit a single class, it is known as hierarchical inheritance. Example: Animal → Dog = Cats
* **Hybrid inheritance** - Hybrid inheritance is a combination of multiple and multi-level inheritances.

#### Advantages 
The main advantages of inheritance are code reusability and readability. When a child class inherits the properties and functionality of the parent class, we need not to write the same code again in the child class. This makes it easier to reuse the code, makes us write less code and the code becomes much more readable.

#### Real Life Example
If there is a class such as ‘vehicle’, other classes like ‘car’, ‘bike’, etc can inherit common properties from the vehicle class.


### What is Overloading and Overriding? 

When two or more methods in the same class have the same name but different parameters, it's called Overloading. <BR/>

When the method name and parameters are the same in the superclass and the child class, it's called Overriding. <BR/>

SL | Overloading  | Overriding   | 
--- | --- | --- | 
1 | Method overloading is a compile-time polymorphism.| Method overriding is a run-time polymorphism.|
2 |It helps to increase the readability of the program.|It is used to grant the specific implementation of the method which is already provided by its parent class or superclass.|
3 |	It occurs within the class.|It is performed in two classes with inheritance relationships.|
4 |Method overloading may or may not require inheritance. |Method overriding always needs inheritance.|
5 |In method overloading, methods must have the same name and different signatures. |In method overriding, methods must have the same name and same signature.|
6 |	In method overloading, the return type can or can not be the same, but we just have to change the parameter. |In method overriding, the return type must be the same or co-variant.|
