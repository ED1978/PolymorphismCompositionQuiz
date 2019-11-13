POLYMORPHISM

1.  Literally Change (Poly)  Form (Morph).  Or the ability
of an object to change it's form.

2.  In the case of OO design and particularly Java, it     would be the ability of an object to change it's type, specifically an object of type <TYPE> becomes <IType> when it implements an interface.  Another example is that a child class could take on the form of any of it's superclasses i.e. A Fiat Panda can be a Taxi, a Car or a Vehicle.

3.  We can use interfaces and inheritance to implement polymorphism in Java.

4.  Potentially infinite depending on how many classes sit higher in the hierarchy.

5.  When 2 classes implement the same interface, they can take on the both the form of the class and the interface.  So in it's own context, an objects form is it's own class, but in the context of say an arraylist<INTERFACE>, the object then takes the form of <INTERFACE>.


COMPOSITION

6 & 7.  Composition in OO programming considers the ownership of one class of another, for example, an engine belongs to it's car or a car HAS an engine.  Another way of describing it would be that a car is composed of an engine etc etc. In the car analogy, the classes do not share functionality so do not inherit from one another, but they both conceptually require each other to function.

8.  For me at least, the concept helps me to visualise how classes sit within and interact with each other. It also helps with encapsulation and the separation of concerns.

9.  All if it's composing objects are destroyed with it.
