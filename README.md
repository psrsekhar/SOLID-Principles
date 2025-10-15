# SOLID Principles

A comprehensive guide to understanding and applying the **SOLID principles** of object-oriented programming (OOP).  
These principles form the foundation of **clean, maintainable, and scalable** software design.

---

## 📘 Overview

The **SOLID** principles are a set of five design principles that help developers write code that is easier to manage, extend, and test.  
This repository provides clear **concept explanations**, **bad vs. good code examples**, and **practical scenarios** demonstrating each principle.

---

## 🧩 The SOLID Principles

### 1. **S — Single Responsibility Principle (SRP)**
> A class should have only one reason to change.

- Focuses on keeping classes small and focused.  
- Each class should handle only one responsibility.  

### 2. **O — Open/Closed Principle (OCP)**
> Software entities should be open for extension, but closed for modification.

- Allows behavior to be extended without modifying existing code.  
- Encourages use of abstractions, interfaces, and inheritance carefully.

### 3. **L — Liskov Substitution Principle (LSP)**
> Subtypes must be substitutable for their base types.

- Derived classes should not break the functionality of base classes.  
- Promotes reliable polymorphism.

### 4. **I — Interface Segregation Principle (ISP)**
> Clients should not be forced to depend on interfaces they do not use.

- Encourages splitting large interfaces into smaller, specific ones.  
- Helps avoid unnecessary dependencies.

### 5. **D — Dependency Inversion Principle (DIP)**
> Depend on abstractions, not on concretions.

- High-level modules should not depend on low-level modules.  
- Both should depend on abstractions (e.g., interfaces).

---

## 🧠 Learning Objectives

By exploring this repository, you will:

- Understand the intent and importance of each SOLID principle.  
- Identify design flaws and refactor them using SOLID concepts.  
- Learn how to apply principles to build flexible, extensible, and testable systems.  
- Strengthen your understanding of clean code and software architecture.

---

## 📂 Repository Structure

- Single-Responsibility/ — Examples demonstrating the Single Responsibility Principle (SRP), showing how each class should have only one reason to change.
- Open-Closed/ — Illustrates the Open/Closed Principle (OCP), emphasizing how code can be extended without modifying existing components.
- Liskov-Substitution/ — Explains the Liskov Substitution Principle (LSP), ensuring that subclasses can replace their parent classes without breaking behavior.
- Interface-Segregation/ — Covers the Interface Segregation Principle (ISP), advocating for smaller, specific interfaces instead of large, general ones.
- Dependency-Inversion/ — Demonstrates the Dependency Inversion Principle (DIP), focusing on depending on abstractions rather than concrete implementations.
- README.md — Contains project overview, principles explanation, and learning resources.


Each folder includes:
- Concept explanation  
- Example of violation (bad design)  
- Refactored version (SOLID-compliant design)  
- Key takeaways and notes  

---

## 🧩 Example Format

Each example typically includes:

| Section | Description |
|----------|--------------|
| ❌ Bad Example | Demonstrates a violation of the principle |
| ✅ Refactored Example | Applies SOLID principle to fix design issues |
| 💡 Key Takeaway | What was improved and why it matters |

---

## 🧭 Further Reading

- [SOLID Principles by Robert C. Martin (Uncle Bob)](https://en.wikipedia.org/wiki/SOLID)
- [Clean Code by Robert C. Martin](https://www.goodreads.com/book/show/3735293-clean-code)
- [Design Principles and Design Patterns](https://blog.cleancoder.com/)
- [Refactoring Guru — SOLID Overview](https://refactoring.guru/design-patterns/solid)

---

## 💬 Contributing

Contributions are welcome!  
If you’d like to add examples in your preferred programming language or improve explanations, feel free to open a pull request.

---

## 🏷️ Topics

`SOLID` • `OOP` • `Clean Code` • `Design Principles` • `Software Architecture` • `Best Practices`

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use and modify for learning or teaching purposes.
