
# Comprehensive Tutorial on C# Classes

## Introduction

This tutorial provides an in-depth understanding of C# classes, a fundamental concept in object-oriented programming (OOP). We'll cover the definition, structure, and usage of classes in C#.

### What is a Class in C#?

A class in C# is a blueprint for creating objects. It defines properties, fields, methods, and events. A class encapsulates data and the methods that operate on the data.

### Defining a Class in C#

**Example: Basic Class Definition**
```csharp
public class Person
{
    // Fields
    public string Name;
    public int Age;

    // Constructor
    public Person(string name, int age)
    {
        Name = name;
        Age = age;
    }

    // Method
    public void Greet()
    {
        Console.WriteLine($"Hello, my name is {Name} and I am {Age} years old.");
    }
}
```

### Creating and Using Objects

Objects are instances of a class. They are created using the `new` keyword followed by the class name and constructor.

**Example: Creating and Using an Object**
```csharp
Person person = new Person("Alice", 30);
person.Greet(); // Output: Hello, my name is Alice and I am 30 years old.
```

### Conclusion

Classes are the foundation of object-oriented programming in C#. They provide a structured approach to building applications by encapsulating data and behavior.

### Further Learning
- Explore inheritance and polymorphism with classes.
- Implement interfaces and abstract classes.
- Understand the principles of encapsulation and data hiding.
