

# Week_2_Assignment

This repository contains solutions for Week 2's Java programming assignments. It includes three classes:

1. **Person**: A class representing a person with attributes like `name` and `age`, and methods to display these attributes.
2. **BankAccount**: A class simulating basic banking operations such as deposit, withdrawal, and balance check.
3. **Rectangle**: A class demonstrating constructors, method overloading, and calculation of areas for both squares and rectangles.

---

## Classes

### 1. Person

The `Person` class stores basic information about a person and displays it.

- **Attributes**:
  - `name`: The person's name.
  - `age`: The person's age.

- **Methods**:
  - `display()`: Displays the name and age of the person.

- **Usage**:
  - Creates a `Person` object with a constructor and displays their details.

#### Example:

### 2. BankAccount

The `BankAccount` class simulates a basic banking system where users can deposit, withdraw, and check their balance.

- **Attributes**:
  - `balance`: Stores the current balance of the account.

- **Methods**:
  - `deposite(double amount)`: Adds the specified amount to the balance.
  - `withdrowal(double amount)`: Deducts the specified amount if there are sufficient funds.
  - `displayBalance()`: Displays the current account balance.

- **Usage**:
  - Allows the user to deposit, withdraw, and check their balance interactively.

#### Example:
```
BankAccount account = new BankAccount();
account.deposit(1000); // Deposits 1000
account.withdraw(500); // Withdraws 500
account.displayBalance(); // Displays the current balance
```

### 3. Rectangle

The `Rectangle` class demonstrates constructors and method overloading for calculating areas of squares and rectangles.

- **Attributes**:
  - `length`: Length of the rectangle.
  - `width`: Width of the rectangle.

- **Constructors**:
  - `Rectangle(double side)`: Initializes a square with equal length and width.
  - `Rectangle(double length, double width)`: Initializes a rectangle with specified length and width.

- **Methods**:
  - `calculateAria()`: Calculates the area based on the object’s length and width.
  - `calculateAria(double length, double width)`: Calculates the area for custom dimensions.
  - `display()`: Displays the dimensions and calculated area.

#### Example:
```
Rectangle square = new Rectangle(10);
square.display();

Rectangle rectangle = new Rectangle(20, 30);
rectangle.display();

double customArea = rectangle.calculateAria(5, 10);
System.out.println("Custom Area: " + customArea);
```

---

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/AmolNisargan/amol_nisargan_week2_assignment.git
   ```
2. Compile the classes:
   ```bash
   javac Week_2_Assignment/*.java
   ```
3. Run each class individually:
   ```bash
   java Week_2_Assignment.Person
   java Week_2_Assignment.BankAccount
   java Week_2_Assignment.Rectangle
   ```

---

## Author

*Amol Nisargan*

---
