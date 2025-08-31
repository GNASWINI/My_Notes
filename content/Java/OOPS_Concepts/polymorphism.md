---
title: Polymorphism
---

# Polymorphism in Java

**Definition:**  
Polymorphism means **one name, many forms**.  
In Java, this happens via **method overloading** and **method overriding**.

**Real-world Example:**  
- A **person** can be a **teacher** at school, a **customer** at a shop, and a **player** at a club — different roles, same person.  

**Java Example (Overriding):**
```java
class Animal {
    void sound() {
        System.out.println("Animal makes a sound");
    }
}

class Dog extends Animal {
    void sound() {
        System.out.println("Dog barks");
    }
}

class Cat extends Animal {
    void sound() {
        System.out.println("Cat meows");
    }
}
```
👉 Same `sound()` method, but different output depending on the object.
