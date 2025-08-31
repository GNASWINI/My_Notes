# Abstraction in Java

**Definition:**  
Abstraction means **hiding implementation details** and showing only the **essential features**.  
We achieve this using **abstract classes** or **interfaces**.

**Real-world Example:**  
- When you drive a **car**, you use the **steering wheel** and **pedals**,  
  but you don’t know exactly how the **engine** or **braking system** works internally.

**Java Example:**
```java
abstract class Vehicle {
    abstract void drive(); // abstract method
}

class Bike extends Vehicle {
    void drive() {
        System.out.println("Bike is driving...");
    }
}

class Car extends Vehicle {
    void drive() {
        System.out.println("Car is driving...");
    }
}
```
👉 The user just calls `drive()` without worrying about how it’s implemented.
