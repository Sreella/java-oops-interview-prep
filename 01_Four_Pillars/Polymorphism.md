# Polymorphism

## 1. Definition

Polymorphism allows the same method name to have different behaviors depending on the context.

It means "many forms".

---

## 2. Types of Polymorphism

### 1. Compile-Time Polymorphism (Method Overloading)
- Same method name
- Different parameters
- Resolved at compile time

### 2. Runtime Polymorphism (Method Overriding)
- Same method signature
- Occurs in parent-child classes
- Resolved at runtime using dynamic method dispatch

---

## 3. Code Example (Overloading)

```java
class Calculator {
    int add(int a, int b) {
        return a + b;
    }

    double add(double a, double b) {
        return a + b;
    }
}

**## 4. Code Example (Overriding)**
class Animal {
    void sound() {
        System.out.println("Some sound");
    }
}

class Dog extends Animal {
    @Override
    void sound() {
        System.out.println("Bark");
    }
}

**## 5. Key Interview Points**
Overloading = compile-time polymorphism

Overriding = runtime polymorphism

Achieved through dynamic method dispatch

Improves flexibility and scalability
