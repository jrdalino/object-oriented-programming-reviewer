# Object Oriented Programming

## Object Oriented Fundamentals
- Classes: Constructors are methods that gets called when you create a new instance of the class
- Coupling: Problem - How much a class is coupled or dependent on another class
- Interfaces: A Contract that specifies the capabilities that a class should provide. Solution to coupling.
- Encapsulation: private and public are examples of access modifiers. Use getters and setters
- Abstraction: Reduce complexity by hiding unnessary details.
- Inheritance: Mechanism for reusing code across classes
- Polymorphism: Ability of object to take on many forms. Abstract class and method.

## Principles of Design - S.O.L.I.D.
- Single Responsibility: a class should only have one responsibility
- Open/Closed: classes should be open for extension, but closed for modification
- Liskov Substitution: if class A is a subtype of class B, then we should be able to replace B with A without disrupting the behavior of our program
- Interface Segregation: larger interfaces should be split into smaller ones
- Dependency Inversion: instead of high-level modules depending on low-level modules, both will depend on abstractions

## Software Development Processes
- Software Project Cycle: Planning (Business Modeling) > Requirements > Analysis > Design > Implementaton > Test > Deployment (Software Product) > Evaluation & Maintenance
- Object Oriented Analysis and Design: URS > Requirements Modeling > Use Case Model > Analysis Modeling > Analysis Model > Design Modeling > Design Model > Software Architecture
- Incremental and Iterative Model
- Agile Model: Extreme Programming & Scrum
- Scrum: Product Owner interviews Stakeholders and adds Items to Product Backlog > Team does Spring Planning > Spring Backlog > Daily Scrum + Sprint + Product Backlog Refinement > Potentially Shippable Product Increment > Spring Review + Retrospective
- Agile Model Driven Development (AMDD)

## Unified Modeling Language (UML)
- Introduction: https://www.geeksforgeeks.org/unified-modeling-language-uml-introduction/?ref=lbp
- Overview: https://www.geeksforgeeks.org/unified-modeling-language-uml-class-diagrams/?ref=lbp
- Conceptual Model: https://www.geeksforgeeks.org/conceptual-model-of-the-unified-modeling-language-uml/?ref=lbp
- UML > Behavioral > Interaction > Sequence Diagrams https://www.geeksforgeeks.org/unified-modeling-language-uml-sequence-diagrams/?ref=lbp
- UML > Structural > Class Diagrams

## Design Patterns

### Behavioral Patterns
#### Strategy **
- Client selects the ConcreteStrategy via the Context
- Context
- Strategy defines an interface for a family of algorithms
- ConcreteStrategy implements a compliant algorithm
#### Iterator **
- Client runs createIterator()
- Iterator defines an interface for accessing and traversing Aggregate
- ConcreteIterator
- Aggregate
- ConcreateAggregator create ConcreteIterator
#### Memento **
- Originator
- Memento
- Caretaker
#### Observer **
- Subject
- ConcreteSubject
- Observer
- ConcreteObserver
#### Command **
- Client
- Invoker
- Command
- ConcreteCommand
- Receiver
#### State
- Context
- State
- ConcreteState
#### Template Method
- AbstractClass
- ConcreteClass
#### Mediator
#### Chain of Responsibility
#### Visitor
#### Interpreter

### Structural Patterns
#### Bridge **
#### Composite **
- Client
- Component
- Leaf
- Composite
#### Decorator **
- Component
- ConcreteComponent
- Decorator
- ConcreteDecorator
#### Adapter
#### Facade
#### Flyweight
#### Proxy

### Creational Patterns
#### Factory Method **
- Creator defines an interface for creating a Product
- ConcreteCreator decides which ConcreteProduct to create
- ConcreteProduct
- Product
#### Builder
#### Singleton
#### Abstract Factory
#### Prototype

## References:
- Design Patterns: Elements of Reusable Object-Oriented Software” by Erich Gamma, Richard Helm, Ralph Johnson and John Vlissides
- NICF- Object Oriented Design Patterns (SF) References: https://www.iss.nus.edu.sg/executive-education/course/detail/nicf--object-oriented-design-patterns-(sf)/software-systems
- General: https://www.geeksforgeeks.org/software-engineering/
- OO Concepts: https://documentation.progress.com/output/ua/OpenEdge_latest/index.html#page/gsdev/object-oriented-concepts-overview.html
- UML Diagrams: https://www.geeksforgeeks.org/unified-modeling-language-uml-introduction/
- Programming Foundations ‐ Object‐Oriented Design from lynda.com: https://www.lynda.com/Python-tutorials/Programming-Foundations-Object-Oriented-Design/731735-2.html
- OO Modelling with Software Design Principles: (Object‐Oriented Design: https://www.coursera.org/learn/object-oriented-design
- UML and Object‐Oriented Design Foundations: https://www.udemy.com/course/uml-and-object-oriented-design-foundations/
- UML Specification by OMG: https://www.omg.org/spec/UML#document%E2%80%90metadata
