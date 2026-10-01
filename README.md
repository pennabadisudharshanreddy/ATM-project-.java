# ATM Project (Java)

A menu-driven console ATM simulation built in Java to practice Object-Oriented Programming concepts.

## Features
- Create a savings account with holder name, account number and initial balance
- Deposit money
- Withdraw money with insufficient balance check
- Check current balance
- Display account details
- Menu-driven interface using do-while loop (runs until Exit)

## OOP Concepts Used
- **Interface**: `BankOperations` (deposit, withdraw, checkBalance)
- **Abstraction**: `BankAccount` abstract class implements the interface
- **Encapsulation**: private fields with getters and setter
- **Inheritance**: `SavingsAccount` extends `BankAccount`
- **Polymorphism**: method overriding using `@Override`
- **Constructors**: including `super()` call in the child class

## Sample Menu
    ===== BANK MENU =====
    1. Deposit
    2. Withdraw
    3. Check Balance
    4. Display Account Details
    5. Exit

## How to Run
1. Install JDK 8 or above
2. Download `AtmProject.java`
3. Compile: `javac AtmProject.java`
4. Run: `java AtmProject`

## Tech Stack
- Java
- VS Code

## Author
Pennabadi Sudharshan Reddy
