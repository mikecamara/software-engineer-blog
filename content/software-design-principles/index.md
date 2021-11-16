---
title: Software Design Principles
date: "2021-11-06T22:12:03.284Z"
description: "Learn how to handle complex projects"
---

Software Design Principles (SDP) help us to build maintainable and scalable software.

The word 'principle' comes from the Latin principium ‘source’, principia (plural) ‘foundations’, from princeps, princip- ‘first, chief and the definition is a fundamental truth or proposition that serves as the foundation for a system of belief or behaviour or for a chain of reasoning.

The principles in software are concepts that guide engineer as a source of truth.

In this post I will introduce SDP concepts such as UML, Design Patterns, SOLID Principles, and aspects of high-level design. 

The concept of software architecture relates to the planning aspects of the software, it explore and define how all the components of the system will work and interact.

SDP focus on defining guidelines and tools that enable a system resilience, including:

* Each system part or component should have a well defined task and function in the overall system.

* Only add parts that you are going to use now.

* Keep it simple

* Don't repeat code

Object-oriented programing (OOP) is a programming paradigm which is a method to organise programs while promoting maintanability. In comparison, another two computer paradigm are Procedural and Functional

Objects contains data and behaviour in a container.

Object oriented helps engineers to build maintainable and scalabel and is supported by four pillars, namely:

- Encapsulation - We have classes and we have self contained encapsulated objects of that class in the code with functions and variables.
- Abstraction - This means hiding parts of the code that you wouldn't like to expose.
- Inheritance - DRY - reuse and extend functionalities
- Polymorphism - Add specifics functions to your classes mutating into a differnt class from the same type  

Engineers shouldn't need to look at the code to understand how it works. 
 
Unified Modeling Language (UML) is a graphic way to represent your system representing objects and their interactions in high-level diagrams.

These diagrams expose the interactions with the system and guide developers to the code implementation.

 There are 14 distinct types of UML diagrams, divided into two categories structure diagrams and behavioral diagrams. 

## Structure Diagrams
* Class Diagram
* Component Diagram
* Deployment Diagram
* Object Diagram
* Package Diagram
* Profile Diagram
* Composite Structure Diagram

## Behavioral Diagrams
* Use Case Diagram
* Activity Diagram
* State Machine Diagram or State Charts Diagrams
* Sequence Diagram
* Communication Diagram
* Interaction Overview Diagram
* Timing Diagram

- Class Diagram documents object name, methods and attributes

- System Diagram and Flowcharts are diagrams that give engineers a birs's-eye view of the complexity of the overall system integration including front and back-end.

Each type of diagram have its pros and cons, and usually suit a specific need of the system documentation.

The SOLID Principles are a set of guidelines for creating well-sesigned classes.

SOLID stands for:

* Single Responsibility: Classes should have only one reason to change
* Open-Closed: Instead of refactor existing classes, add new features by extension.
* Liskov Substitution: Replacing a subclass with a parent class should work
* Interface Segregation: Interfaces methods and attributes should be usable to its subclasses.
* Dependency Inversion Principle: Classes interact with interfaces instead of concrete classes.

Design Patterns relates to how we organise the pieces of code the compose the system in a way that enables maintainability.

Types of Design Patterns applicable for OOP: 
* Creational - hide logic
* Structural - object structures
* Behavioral - define interactions

An example of Creational pattern is the Singleton pattern which is suitable for when we only need to create one intance of an object, for instance some configuration file.

The Observer pattern is an example of Behavioral pattern that is used to receive notifications in regards to events that occur in a object.

Design patterns are best o choose when the issue is occuring.

The Model View Controller (MVC) design architectural pattern which establishes the model as the place where the data and the classes related to the data are organized, the View is where the UI elements that interact with the user are organized and controller is where the logic of the system lives. 

MVVM

An alternative to MVC or MVVM is VIPER, an architectural pattern for iOS application architecture which is used to build large projects. It divides the application in five groups: View, Interactor, Presenter, Entity and Routing. This conforms to the Single Responsibility Principle.

`'we shape our buildings and afterwards our buildings shape us.' - Sir Winston Churchill.`

The software you build will shape the engineer you will become. Good software architecture will enable the system to be maintable and scalable.

VIPER can be used in association with SwiftUI and Combine to support building a clean architecture, separating UI, business logic, data and networking. This makes the code maintainable, and easier to implement tests.

VIPER offers an alternative to this scenario and can be used in conjunction with SwiftUI and Combine to help build apps with a clean architecture that effectively separates the different functions and responsibilities required, such as the user interface, business logic, data storage and networking. These are then easier to test, maintain and expand.



[UML Official Site](https://www.uml.org/)
[Design Patterns by Refactoring Guru](https://refactoring.guru/design-patterns)
[Clean Coders: Software Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)
[Course Software Design Principles](https://www.codecademy.com/learn/software-design-principles)