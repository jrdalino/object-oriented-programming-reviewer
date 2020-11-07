# Object Oriented Programming

## Prerequisite: Object Oriented Fundamentals
- Classes: Constructors are methods that gets called when you create a new instance of the class
- Coupling: Problem - How much a class is coupled or dependent on another class
- Interfaces: A Contract that specifies the capabilities that a class should provide. Solution to coupling.
- Encapsulation: private and public are examples of access modifiers. Use getters and setters
- Abstraction: Reduce complexity by hiding unnessary details.
- Inheritance: Mechanism for reusing code across classes
- Polymorphism: Ability of object to take on many forms. Abstract class and method.

## Prerequisite: Principles of Design - SOLID
- Single Responsibility: a class should only have one responsibility
- Open/Closed: classes should be open for extension, but closed for modification
- Liskov Substitution: if class A is a subtype of class B, then we should be able to replace B with A without disrupting the behavior of our program
- Interface Segregation: larger interfaces should be split into smaller ones
- Dependency Inversion: instead of high-level modules depending on low-level modules, both will depend on abstractions

## Prerequisite: Software Development Processes
- Software Project Cycle: Planning (Business Modeling) > Requirements > Analysis > Design > Implementaton > Test > Deployment (Software Product) > Evaluation & Maintenance
- Object Oriented Analysis and Design: URS > Requirements Modeling > Use Case Model > Analysis Modeling > Analysis Model > Design Modeling > Design Model > Software Architecture
- Incremental and Iterative Model
- Agile Model: Extreme Programming & Scrum
- Scrum: Product Owner interviews Stakeholders and adds Items to Product Backlog > Team does Spring Planning > Spring Backlog > Daily Scrum + Sprint + Product Backlog Refinement > Potentially Shippable Product Increment > Spring Review + Retrospective
- Agile Model Driven Development (AMDD)

## Prerequisite: Unified Modeling Language (UML)
- Introduction: https://www.geeksforgeeks.org/unified-modeling-language-uml-introduction/?ref=lbp
- Overview: https://www.geeksforgeeks.org/unified-modeling-language-uml-class-diagrams/?ref=lbp
- Conceptual Model: https://www.geeksforgeeks.org/conceptual-model-of-the-unified-modeling-language-uml/?ref=lbp

### UML > Behavioral
- Activity Diagrams https://www.geeksforgeeks.org/unified-modeling-language-uml-activity-diagrams/?ref=lbp
- Interaction > Sequence Diagrams https://www.geeksforgeeks.org/unified-modeling-language-uml-sequence-diagrams/?ref=lbp
- Interaction > Communication Diagrams
- Interaction > Timing Diagrams
- State Machine Diagrams https://www.geeksforgeeks.org/unified-modeling-language-uml-state-diagrams/?ref=lbp
- Use Case Diagrams

### UML > Structural
- Class Diagrams
- Component Diagrams
- Composite Structure Diagrams
- Deployment Diagrams
- Object Diagrams https://www.geeksforgeeks.org/unified-modeling-language-uml-object-diagrams/?ref=lbp
- Package Diagrams

## Design Patterns
- 1.a Solving Design Problems using Patterns
- 1.b Design Patterns in Software Development Process
- 2 Principles of Design
- 3 Understanding Design Patterns > Workshop 1
- 4 Applying Design Patterns (Structural) > Workshop 2
- 5 Applying Design Patterns (Behavioural) > Workshop 3
- 6 Selecting and Using Design Patterns > Workshop 4
- 7 Refactoring to Patterns
- 8 Design Case Study > Presentations

### Behavioral Patterns
#### Memento
- Without violating encapsulation, capture and externalize an object's internal state so that the object can be restored to this state later.
#### State
- Allow an object to alter its behavior when its internal state changes. The object will appear to change its class.
#### Iterator
- Provide a way to access the elements of an aggregate object sequentially without exposing its underlying representation.
#### Strategy **
- Define a family of algorithms, encapsulate each one, and make them interchangeable. Strategy lets the algorithm vary independently from clients that use it.
- Strategy defines an interface for a family of algorithms
- ConcreteStrategy implements a compliant algorithm
- Client selects the ConcreteStrategy via the Context
#### Template Method
- Define the skeleton of an algorithm in an operation, deferring some steps to subclasses. Template Method lets subclasses redefine certain steps of an algorithm without changing the algorithm 's structure.
#### Command
- Encapsulate a request as an object, thereby letting you parameterize clients with different requests, queue or log requests, and support undoable operations.
#### Observer
- Define a one-to-many dependency between objects so that when one object changes state, all its dependents are notified and updated automatically.
#### Mediator
- Define an object that encapsulates how a set of objects interact. Mediator promotes loose coupling by keeping objects from referring to each other explicitly, and it lets you vary their interaction independently.
#### Chain of Responsibility
- Avoid coupling the sender of a request to its receiver by giving more than one object a chance to handle the request. Chain the receiving objects and pass the request along the chain until an object handles it.
#### Visitor
- Represent an operation to be performed on the elements of an object structure. Visitor lets you define a new operation without changing the classes of the elements on which it operates.
#### Interpreter
- Given a language, define a represention for its grammar along with an interpreter that uses the representation to interpret sentences in the language.

### Structural Patterns
#### Composite
- Compose obje cts into tree structures to represent part-whole hierarchies. Composite lets clients treat individual objects and compositions of objects uniformly.
#### Adapter
- Convert the interface of a class into another interface clients expect. Adapter lets cl asse swork together that couldn't otherwise because of incompatible interfaces.
#### Decorator
- Attach additional responsibilities to an object dynamica lly. Decorators provide a flexible alternative to subclassing for extending functionality.
#### Facade
- Provide a unified interface to a set of interfaces in a subsystem. Facade defines a higher-level interfa ce that makes the subsystem easier to use.
#### Flyweight
- Use sharing to support large numbers of fine-grained objects efficiently.
#### Bridge
- Decouple an abstraction from its implementation so that the two canvary independently.
#### Proxy
- Provide a surrogate or placeholder for another object to control access to it.

### Creational Patterns
#### Abstract Factory
- Provide an interface for creating families of related or dependent objects without specifying their concrete cl asses
#### Builder
- Separate the construction of a complex object from its representation so that the same construction process can create different representations
#### Factory Method **
- Define an interface for creating an object, but let subclasses decide which class to instantiate. Factory Method lets a class defer instantiation to subclasses.
#### Prototype
- Specify the kinds of obj ectsto crea te using a prototypical instance, and create new objec ts by copying this prototype.
#### Singleton
- Ensure a class only has one instance, and provide a global point of access to it.

## References:
- Design Patterns: Elements of Reusable Object-Oriented Software” by Erich Gamma, Richard Helm, Ralph Johnson and John Vlissides
