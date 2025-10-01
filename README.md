# Inheritance in C++

## Aim
To study and implement different types of **Inheritance** in C++.

## Software Required
- Visual Studio  

---

## Theory
Inheritance is a fundamental concept in **Object-Oriented Programming (OOP)**.  
It allows one class to inherit the **data members** and **functions** of another class.  
A derived class can reuse methods and fields from its base class, reducing redundancy and improving code organization.

### Types of Inheritance in C++
1. **Single Inheritance**  
   A subclass is derived from a single parent class.  

2. **Multiple Inheritance**  
   A subclass inherits from more than one parent class.  

3. **Multilevel Inheritance**  
   A class is derived from another derived class, forming a chain of inheritance.  

4. **Hierarchical Inheritance**  
   Multiple subclasses inherit from a single base class.  

---

### Advantages of Inheritance in C++
- **Code Reusability** – Avoids duplication by reusing existing code.  
- **Abstraction** – Supports abstract classes to enforce a common interface.  
- **Class Hierarchy** – Models real-world relationships naturally.  
- **Polymorphism** – Enables both compile-time (overloading) and runtime (virtual functions) polymorphism.  

---

## Implementation
To demonstrate inheritance in C++, the following programs have been implemented:
- Single Inheritance  
- Multiple Inheritance  
- Multilevel Inheritance  
- Hierarchical Inheritance  
- Access Specifier in Inheritance (Protected Members)  

---

## Algorithms

### Algorithm: Single Inheritance (Animal → Dog)
1. Start  
2. Define base class `Animal` with function `eat()`.  
3. Define derived class `Dog` that inherits `Animal` and has function `bark()`.  
4. In `main()`:  
   - Create object `myDog`.  
   - Call `eat()` and `bark()`.  
5. End  

---

### Algorithm: Multiple Inheritance (Car ← Vehicle + Specs)
1. Start  
2. Define base class `Vehicle` with member `company` and function `type()`.  
3. Define base class `Specs` with member `mileage` and function `colour()`.  
4. Define class `Car` inheriting from both `Vehicle` and `Specs`.  
5. In `main()`:  
   - Create object `f2`.  
   - Call inherited functions and print data members.  
6. End  

---

### Algorithm: Multilevel Inheritance (Book → Title → Library)
1. Start  
2. Define base class `Book` with member `genre` and function `type()`.  
3. Define class `Title` inheriting from `Book`, with member `title`.  
4. Define class `Library` inheriting from `Title`, with member `name`.  
5. In `main()`:  
   - Create object `b3`.  
   - Access inherited and own members.  
6. End  

---

### Algorithm: Hierarchical Inheritance (Fruit → Apple/Banana/Cherry)
1. Start  
2. Define base class `Fruit` with array `type[3]` and function `supplier()`.  
3. Define `Apple`, `Banana`, `Cherry` classes, each inheriting `Fruit` and having `color`.  
4. In `main()`:  
   - Create objects for `Apple`, `Banana`, and `Cherry`.  
   - Access supplier, type, and color for each.  
5. End  

---

### Algorithm: Accessing Protected Members
1. Start  
2. Define base class `Parent` with `protectedValue`.  
3. Define derived class `Child` with function `showProtected()` to access `protectedValue`.  
4. In `main()`:  
   - Create object `obj`.  
   - Call `showProtected()`.  
5. End  

---

## Conclusion
The above programs demonstrate different types of **Inheritance** in C++: single, multiple, multilevel, hierarchical, and accessing protected members.  
This illustrates how inheritance enables **code reusability, abstraction, class hierarchies, and polymorphism**, making it a cornerstone of object-oriented design.  
