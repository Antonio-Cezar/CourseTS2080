Lecture 6.
Class Diagrams
-	Describes the types of objects that can be created
-	Attributes of the classes
-	Any variable that is bound in a class 
-	Operations of class that can occur
    o   Shows the methods
-	Relationships between these objects

Relationships between objects
-	Association
    o   Association: A and B can call each other
    o   An association is a solid line between two classes, directed from the source class to the target class. The name of the property goes at the 
        target end of the association, together with its multiplicity. 
    o   The multiplicity of a property is an indication of how many objects may fill the property. Lower bound and upper bound are usually defined but not 
        always.
    o   Type A: 1 (an order must have precisely one customer)
    o	Type B: 0..1 (a corporate customer may or may not have a single sale rep.)
    o	Type C: *(A customer need to place an Order, and there is no upper limit to the number of orders a customer may place – zero or more orders.)
-	Inheritance
    o	Inheritance is the concept of acquiring the resource from parents or base class by the child class
    o   In inheritance, the class which allows its properties to be shared is known as the parent class and the class which acquires the properties from its 
        parent class is known as the child class
    o	Inheritance greatly reduces the need to code again and allows code reusability
-	Composition
    o	Composition: A “has-an” instance of B. B cannot exist without A.
-	Aggregation
    o	Aggregation: A “has-en” instance of B. B can exist without A.
    o	The same as composition.
    o	Aggregation on itself is strictly meaningless.
    o	Ignore it in your own diagrams. If you se it on another diagram you need to understand more of the meaning in use of it.
-	Abstract classes
    o	An abstract class is a particular type of class that cannot be instantiated.
    o	An abstract class is designed to be inherited by subclasses that implement or override its methods
    o	In other words, abstract classes are either partially implemented or not implemented at all
    o	You can have functunality in your abstract class – the methods in an abstract class can be both abstract and concrete
    o	You can take advantage of abstract classes to design components and specify some level of standard functionality that must be implemented by derived classes.
