# C# Inheritance & Polymorphism Demo

This project demonstrates core Object-Oriented Programming (OOP) concepts in C# using a multi-level inheritance hierarchy.

## Concepts Covered
- Multi-level inheritance (Grandparent → Parent → Child)
- Constructor chaining using `base`
- Access modifiers (`public`, `protected`, `private`)
- Method overriding with `virtual` and `override`
- Runtime polymorphism using base-class references

## Structure
- `Grandparent` (base class)
- `ParentA`, `ParentB` (derived classes)
- `SonA`, `SonB` (child classes with overridden behavior)

## Key Example
A base-class reference (`Grandparent`) is used to invoke overridden methods in derived classes at runtime, demonstrating polymorphism.

## Technologies
- C#
- .NET Console Application

## How to Run
```bash
dotnet run

