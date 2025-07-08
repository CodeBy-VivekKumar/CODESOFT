#  Number Guessing Game (Java)

A simple console-based Number Guessing Game built in Java. The game generates a random number between 1 and 100, and the player has to guess it within a limited number of attempts.


##  Features

- Generates a random number between 1 to 100
- User guesses the number with hints ("Too high" / "Too low")
- Limited number of attempts (default: 7)
- Score tracking based on rounds won
- Option to play multiple rounds
- Input validation for incorrect entries


##  How It Works

1. The program picks a random number between 1 and 100.
2. The user has up to 7 chances to guess the number correctly.
3. After each guess, the program informs whether the guess is:
   - Too high
   - Too low
   - Correct
4. If guessed correctly within attempts, the user wins the round.
5. After each round, the user is prompted to play again.
6. At the end, the total rounds and rounds won are displayed.

# Marks Percentage & Grade Calculator (Java)

This is a simple Java console application that takes marks for multiple subjects, calculates the **total marks**, **average percentage**, and assigns a **grade** based on the performance.

---

##  Features

- User input for marks of multiple subjects
- Calculates:
  - Total Marks
  - Average Percentage
  - Grade based on average
- Validates marks (must be between 0 and 100)
- User-friendly messages and formatting

---

##  How It Works

1. User enters the number of subjects.
2. Marks for each subject are entered one by one.
3. The program calculates:
   - Total marks = sum of all subject marks
   - Average percentage = total marks / number of subjects
   - Grade according to percentage
4. Final results are displayed with:
   - Total
   - Percentage
   - Grade

---

## Grading System

| Percentage Range | Grade   |
|------------------|---------|
| 90 - 100         | A+      |
| 80 - 89.99       | A       |
| 70 - 79.99       | B       |
| 60 - 69.99       | C       |
| 50 - 59.99       | D       |
| Below 50         | F (Fail)|

---

# ATM Simulator (Java)

A simple **Java console application** that simulates the functionality of an ATM machine. It allows users to **withdraw**, **deposit**, and **check balance** securely. This project demonstrates object-oriented programming (OOP) principles and basic input/output operations in Java.

---

##  Features

- Console-based user interface
- Bank account linked with the ATM
- Perform:
  - ✅ Check Balance
  - ✅ Deposit Amount
  - ✅ Withdraw Amount (with balance check)
- Input validation and error messages
- Clean and modular code using Java classes and methods

---

##  Class Overview

### 1. `BankAccount.java`
Represents a user's bank account with:
- Balance storage
- Methods for:
  - `withdraw(amount)`
  - `deposit(amount)`
  - `getBalance()`

### 2. `ATM.java`
Acts as the ATM interface for:
- Showing menu options
- Accepting user inputs
- Calling `BankAccount` methods based on user choices

### 3. `ATMSimulator.java`
Main class to run the program. Initializes the `BankAccount` and starts the ATM UI.





# Student Management System (Java Console Application)

This is a **console-based Student Management System** developed in Java. It allows users to manage student records with features such as adding, removing, searching, displaying students, and storing data persistently using file I/O.

##  Features

- ✅ Add a new student
- ✅ Remove a student by roll number
- ✅ Search for a student
- ✅ Display all students
- ✅ Save student data to a file
- ✅ Load student data automatically on startup
- ✅ Input validation to ensure correct and complete entries

##  Student Attributes

Each student record contains:

- Name
- Roll Number
- Grade
- Email






