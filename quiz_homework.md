
Polymorphism And Composition Homework, Quiz..


Polymorphism..

Q.  What does the word 'polymorphism' mean?

A.  The term polymorphism comes from two Greek words: 'poly' meaning 'many' and "morph" meaning 'change'. 
    When we talk of something being 'polymorphic' we mean that it can have 'many forms'.


Q.  What does it mean when we apply polymorphism to OOP design? Give a simple Java example.

A.  We can treat an instance of a class as if it is also another class, and, or type at the same time.  
    Polymorphism can be implemented using both abstract classes, and interfaces, so all classes which inherit from a class can take the type of the superclass. 
    To use an abstract class, we create a superclass which all the connected classes inherit from, or we can also just have one superclass.
    Interfaces also allow us to treat a class as being of another type. When a class implements an interface it gains the type of the interface without the inheritance chain. We can have as many interfaces as we like, too. Rather than just one super class.


Q.  What can we use to implement polymorphism in Java?

A.  Polymorphism can be implemented using both abstract classes, and interfaces, so all classes which inherit from a class can 
    take the type of the superclass. 
    To use an abstract class, we create a superclass which all the connected classes inherit from, or we can also just have one superclass.
    Interfaces also allow us to treat a class as being of another type. When a class implements an interface it gains the type of the interface without the inheritance chain. We can have as many interfaces as we like, too. Rather than just one super class.


Q.  How many 'forms' can an object take when using polymorphism?

A.  The beauty of "polymorphism" is that any type can behave as if it is any of it's super class types as well as it own. 
    Our Desktop can be both a Desktop and an IConnect, like we mentioned earlier. So anything accepting IConnect can accept a Desktop.

    However, it does not apply the other way round. Anything accepting a Desktop does not accept an IConnect. Not every IConnect is a Desktop, But every Desktop is an IConnect.


Q.  Give an example of when you could use polymorphism.

A . Looking back at the Network lab, for example, our Desktop can be both a Desktop and an IConnect, like we mentioned earlier. 
    So anything accepting IConnect can accept a Desktop.

    However, it does not apply the other way round. Anything accepting a Desktop does not accept an IConnect. Not every IConnect is a Desktop, But every Desktop is an IConnect.


Composition, and Aggregation..

Q.  What do we mean by 'composition' in reference to object-oriented programming?

A . When we think about inheritance, and how we can use it to construct our program we are usually concerned with what a thing 'is'.
    When we think about composition we are concerned with what a thing 'has'.

    In terms of the behaviour we can consider what something 'has' to carry out a behaviour, not what it 'is' that gives us that behaviour, for example a method from a superclass.

    We compose objects from other objects in order to get us to the functionality we need. And we’ve been doing this for a while without outright calling it Composition… we’ve had Hotels composed of Rooms.


Q.  When would you use composition? Provide a simple example in Java.

A . In Java, We compose objects from other objects in order to get us to the functionality we need.

    Composition allows a class to use behaviour from a group of other classes, and makes it possible for that behaviour to change at runtime. We swap behaviours in and out like this at runtime we call this the Strategy Pattern.

    For example, in the Wizard Management lab, composition gave us the ability to set the behaviour of the wizard’s fly method utilising setRide as the Strategy Pattern. Th wizard can fly, and by setting the IFly object that they ride, we can change the ‘strategy’ they use to do so.


Q.  Give a difference between composition and aggregation?

A . Aggregation is similar to composition except that the objects can exist independently from the object, which contains them.
    An aggregate object is one, which contains other objects. 

    In our class example we can create the broomstick separately, dragon seperately and then put it into the wizard class when we are building it.  In this sense, we are thinking about what something 'has', a wizard 'has' A broomstick, a wizard 'has' A dragon.

    We are seeing an object as being an aggregation of other objects. This is what we mean when we talk of aggregation in the object-oriented sense.

    Composition, every wizard 'has' a broomstick. Aggregation, a wizard 'may' have a flying object, but they come and go..


Q.  What is/are the advantage(s) of using composition/aggregation?

A . Composition and Aggregation allows a class to use behaviour from a group of other classes, and makes it possible for that
    behaviour to change at runtime. We swap behaviours in and out like this at runtime we call this the Strategy Pattern.

    Aggregation refers to a 'has a' relationship, where an object has other objects. These objects can exist independently so when the owning object is destroyed, the object it 'owned' can still exist.  In aggregation, objects can exist indepedently of the object which it composes


Q.  When using composition, when an object is destroyed, what happens to all the objects it is composed of?

A . All the objects are destroyed alongside the object that ownes them.


Q.  When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

A . Only the object itself is destroyed, as the objects exist independently of the object that owns it.

