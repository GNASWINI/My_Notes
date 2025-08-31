# Encapsulation in Java

**Definition:**  
Encapsulation means **hiding internal details** and showing only what’s necessary.  
We do this using **private variables** + **getter/setter methods**.

**Real-world Example:**  
Think of a **bank account**.  
- You can **deposit** or **withdraw** money.  
- But you **cannot directly access** the bank’s internal balance ledger.  

**Java Example:**
```java
class BankAccount {
    private double balance; // hidden data

    public void deposit(double amount) {
        balance += amount;
    }

    public double getBalance() {
        return balance;
    }
}
```
👉 The `balance` is hidden, but we provide controlled access via `deposit()` and `getBalance()`.
