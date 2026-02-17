# Abstraction

## 1. Definition

Abstraction is the process of hiding implementation details and exposing only essential functionalities to the user.

It focuses on "What to do" instead of "How to do it".

---

## 2. Why Abstraction?

- Reduces complexity
- Improves flexibility
- Promotes clean architecture
- Helps in large-scale systems

---

## 3. Real-World Example

When driving a car, you use the steering wheel and pedals.
You do not see how the engine works internally.

---

## 4. Code Example (Abstract Class)

```java
abstract class Car {
    abstract void startEngine();
}

class Tesla extends Car {
    @Override
    void startEngine() {
        System.out.println("Tesla engine started silently.");
    }
}


## 5. Key Interview Points

Implemented using abstract classes and interfaces

Cannot create object of abstract class

Abstract methods must be overridden

Helps achieve loose coupling
