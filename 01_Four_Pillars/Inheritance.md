# Inheritance

## 1. Definition

Inheritance allows a class (child/subclass) to acquire properties and behavior of another class (parent/superclass).

It promotes code reusability and hierarchical relationships.

---

## 2. Why Inheritance?

- Code reuse
- Logical relationship modeling
- Reduces duplication
- Improves maintainability

---

## 3. Real-World Example

A Dog is an Animal.
Dog inherits eating behavior but has its own unique behavior like barking.

---

## 4. Code Example

```java
class Animal {
    void eat() {
        System.out.println("This animal eats food.");
    }
}

class Dog extends Animal {
    void bark() {
        System.out.println("Dog barks.");
    }
}

## 5. Key Interview Points

Uses "extends" keyword

Represents IS-A relationship

Java does not support multiple inheritance using classes

Supports multilevel inheritance
