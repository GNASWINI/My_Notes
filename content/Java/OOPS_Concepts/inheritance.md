# Inheritance in Java

**Definition:**  
Inheritance means **acquiring properties and behaviors from a parent class**.  
This allows **code reuse**.

**Real-world Example:**  
- A **Car** is a type of **Vehicle**.  
- A **Bike** is also a type of **Vehicle**.  
Both share common features like **speed**, but have different implementations.

**Java Example:**
```java
class Vehicle {
    int speed;
    void run() {
        System.out.println("Vehicle is running...");
    }
}

class Car extends Vehicle {
    void run() {
        System.out.println("Car is running at speed " + speed);
    }
}
```
👉 `Car` inherits from `Vehicle`, so it can reuse and override methods.
