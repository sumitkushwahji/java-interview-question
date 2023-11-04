# java-interview-question

## Object-Oriented Programming (OOP) Concept in java

Object-Oriented Programming (OOP) is a programming paradigm that uses objects and classes for organizing and structuring code. Java is an object-oriented programming language, and it embodies the fundamental OOP concepts. These concepts help in creating well-structured, modular, and reusable code. The core OOP concepts in Java include:

### Class:

A class is a blueprint or a template for creating objects. It defines the properties (fields/attributes) and behaviors (methods) that objects created from the class will have.
```
public class Person {
    String name;
    int age;

    void sayHello() {
        System.out.println("Hello, my name is " + name);
    }
}
```
### Object:

An object is an instance of a class. It represents a real-world entity and encapsulates both data (attributes) and the methods (functions) that operate on the data.
```
Person person1 = new Person();
person1.name = "Alice";
person1.age = 30;
person1.sayHello();
```

### Inheritance:

Inheritance is a mechanism that allows one class (subclass or derived class) to inherit the properties and behaviors of another class (superclass or base class). It promotes code reusability.
```
public class Student extends Person {
    String studentId;
}
```
### Polymorphism:

Polymorphism allows objects of different classes to be treated as objects of a common superclass. It enables method overriding and dynamic method dispatch.
```
Person person = new Student();
```
### Abstraction:

Abstraction is the process of hiding the complex implementation details and showing only the necessary features of an object. Abstract classes and interfaces are used to achieve abstraction.
```
abstract class Shape {
    abstract double area();
}
```
### Encapsulation:

Encapsulation is the concept of bundling data (fields) and methods that operate on the data into a single unit (class). Access to the data is controlled through methods (getters and setters).
```
public class Account {
    private double balance;

    public void deposit(double amount) {
        balance += amount;
    }

    public double getBalance() {
        return balance;
    }
}
```
### Association:

Association represents a relationship between two or more classes. It can be a one-to-one, one-to-many, or many-to-many relationship.
```
class Department {
    // ...
}

class Employee {
    Department department;
    // ...
}
```
### Composition:

Composition is a type of association where one class is composed of one or more other classes as its parts. It's a "whole-part" relationship.
```
class Engine {
    // ...
}

class Car {
    Engine engine;
    // ...
}
```





















