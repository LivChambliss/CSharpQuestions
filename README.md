# CSharpQuestions
Q: What is a namespace?
A declarative region region that provides a scope to identifiers.
Q: What are value types?
They are variables derived from the class System.ValueType, they directly contain data (int, char, and float, stores numbers, alphabets, and floating point numbers) 
Q: What are reference types?
Store references to their data (objects). Two variables can reference the same objects.
Q: What is an automatic property and how is it useful?
Used when no additional logic is required in property accessors. It keeps code clean and condensed.
Q: What is the purpose of using statement?
It provides a convenient syntax that ensures the correct use of IDisposable objects.
Q: What are dynamic type variables?
Avoids compile time type checking. Escapes type checking at compile time; instead, it resolves type at run time.
Q: What is the purpose of the is operator?
Used to dynamically check whether an object is compatible with a given type
Q: What are generics and how is using them useful?
Allows to define the specification of the data type of programming elements in a class or a method, until it is actually used in the program. Allows you to write a class or method that can work with any data type. 
Q: What is the scope of a public member of a class?
Allows a class to expose its member variables and member functions to other functions and objects. Can be accessed from outside class.
Q: Can you create a function that can accept a varying number of arguments?
Yes, you use the params keyword.
Q: How do you sort an array?
Use method Array.Sort(Array)
Q: What is a nullable type and what purpose does it serve?
Data type where you can assign normal range of values as well as null values. It represents missing values.
Q: What is an enumeration?
A set of named integer containts, using enum keyword. They are value data type. They contain its own values and cannot inherit or cannot pass inheritance.
Q: What is inheritance?
Part of OOP that allows you to define a base that provides specific functionality and to define derived classes that either inherit or override that funtionality.
Q: Is multiple inheritance supported?
No
Q: What is the purpose of as operator
Performs certain types of conversions between compatible reference types or nullable types.
Q: What is an object?
Instance of a class that is created dynamically. Created under class types.
Q: What is the difference between a struct and a class?
Class can create a subclass that will inherit parents properties and methods, whereas Structure does not support the inheritance.
Q: What is the difference between continue and break statements?
Break will leave the loop completely and executes the statement after the loop, and Continue leaves the current iteration and executes with the next value in the loop. Break results in termination of the statement to which is applied. 
Q: What is this and how is it used?
Refers to the current instance of the class and is also used as a modifier of the first parameter of an extension method.
Q: What is try and catch and when are they used?
Try block followed by one or more catch clauses, which specify handlers for different exceptions. When an exception is thrown, the program looks for a catch statement to handle the exception. The try code contains the guarded code that may cause the exception.
Q: How is exception handling done?
A try block is used to encapsulate a region of code. When an exception occurs, the Catch block is executed. The finally block allows you to execute certain code if an exception is thrown or not. Last resort code no matter what.
Q: What is finally and what is its purpose?
Finally block will execute when the try/catch block leaves the execution, no matter what condition cause it. It always executes whether the try block terminates normally or terminates due to an exception. The main purpose is to release the system resources.
Q: List the differences between Array and ArrayList.
Array is strongly typed. Can only store specific type of items/elements. Stores fixed number of elements. Size of an Array must be specified at the time of initialization. ArrayList can store any type of items/elements. ArrayList grows automatically and you don’t need to specify size.
Q: What is an object?
Instance of a class that is created dynamically. 
Q: Define constructor.
When a class or struct is created, constructor is called. May have multiple constructors that take different arguments. They enable the programmer to set default values, limit instantiation, and write code that is flexible and easy to read.
Q: When can var be used to declare a variable and how is the type for the variable determined?
When storing a reference to an object of an anonymous type. You cannot use var as the type of anything but locals.
Q: What is an abstract class?
Cannot be instantiated. Designed to be inherited by subclasses that either implement or override its methods. Methods can be both abstract and concrete.
Q: What is an interface?
Contains only the declaration of the methods, properties, and events, but not the implementation. Makes it easy to maintain a program.
Q: What is a method?
Code block that contains a series of statements. Program causes the statements to be executed by calling the method and specifying any required method arguments. 
Q: What is a property?
A member that provides a flexible tool to read and write the value of a private field. Use them as public data members but actually, they are specific methods called accessors.
Q: What is an access specifier?
The scope of accessibility of an object and its members. We control the scope of the member object of a class using access specifiers. 
Q: What access specifiers are supported and what do they mean?
Private, public, internal, protected, and protected internal.
Private: limits accessibility of a member to within the defined type
Public: has no limits, any members or types defined as public can be accessed within the class
Internal: important role when wanting your class members to be accessible within the assembly. Assembly is the produced .dll or .exe from your .NET Language code.
Protected: only when inheritance is used. Any protected type or member becomes accessible when a child is inherited by the parent.
Protected internal: combination of protected and internal both. Protected internal will be accessible within the assembly due to its internal flavor and also via inheritance due to its protected flavor.
Q: What is a collection?
Standardizes the way of which the objects are handled by your program. Contains a set of classes to contain elements in a generalized manner. 
Q: What is a Hash Table?
Represents a collection of key-and-value pairs that are organized based on the hash code of the key. Uses the key to access the elements in the collection. Hash table is used when you need to access elements by using key, and you can identify a useful key value.
