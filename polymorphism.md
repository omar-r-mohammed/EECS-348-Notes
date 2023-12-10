# polymorphism 

polymorphism is a programming concept that allows different types to be treated the same. This allows for us to write code that works the same way for many different objects. 

This includes overloaded functions, like the + operator for concatenating strings. 

Template classes also allow us to define a template behavior for multiple different types. The compiler internally generates the code based upon the template that has been defined.

Pure polymorphism is another capability of cpp that is achieved via inheritance and subtyping. This allows derived classes to be treated as instances of the base class, allowing us to treat objects of derived classes as objects of the base class. 

Dynamic binding invokes the correct method based on the actual type of the object on runtime. 

This puts a supertype in place of a subtype which operates on a base class reference or pointer that works with objects of derived classes as well. This allows for generic code to be written that works with a range of object types. 