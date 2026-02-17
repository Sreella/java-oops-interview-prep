# Encapsulation

## 1. Definition

Encapsulation is the process of binding data (variables) and methods (functions) into a single unit (class) and restricting direct access to internal data using access modifiers.

It ensures data protection and controlled access.

---

## 2. Why Encapsulation?

- Protects sensitive data
- Improves security
- Maintains data integrity
- Makes code easier to maintain

---

## 3. Real-World Example

A bank account hides its balance. Users cannot directly modify it.
They must use methods like deposit() and withdraw().

---

## 4. Code Example

```java
class BankAccount {
    private double balance;

    public void deposit(double amount) {
        balance += amount;
    }

    public double getBalance() {
        return balance;
    }
}
