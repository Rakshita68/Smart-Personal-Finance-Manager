# Smart Personal Finance Manager

A console-based Personal Finance Management System developed in C++ that helps users track expenses, organize spending into categories, and analyze financial habits. The application stores data using JSON files and provides an interactive command-line interface for managing personal finances efficiently.

---

## Project Overview

Smart Personal Finance Manager is designed to help users record and monitor their daily expenses. Users can categorize expenses, view spending history, search expenses by category, generate summaries, and analyze their spending patterns.

The project demonstrates the use of Object-Oriented Programming (OOP), file handling, JSON data storage, and command-line application development using C++.

---

## Features

- Add expenses with category, description, and amount
- View all recorded expenses
- Search expenses by category
- Delete expenses using Expense ID
- Display total expense summary
- Display monthly expense summary
- Store expense records permanently using JSON
- Interactive Command Line Interface (CLI)

---

## Technologies Used

- C++
- STL (Vectors, Strings, Streams)
- JSON for Modern C++ (nlohmann/json)
- File Handling
- Object-Oriented Programming

---

## Project Structure

```
Expense_Tracker.cpp
expenses.json
json.hpp
README.md
```

---

## Installation

### Prerequisites

- C++ Compiler (GCC / MinGW)
- Visual Studio Code (Recommended)
- nlohmann/json library

### Compile

```bash
g++ Expense_Tracker.cpp -o Expense_Tracker.exe -std=c++17
```

### Run

```bash
.\Expense_Tracker.exe
```

---

## Available Commands

```bash
add Food "Lunch" 150
add Travel "Bus Ticket" 50

list

search Food

delete 2

summary

summary 6

clear

exit
```

---

## Example Usage

### Add Expense

```bash
expense-tracker add Food "Lunch" 150
Expense added successfully (ID: 1)
```

### View Expenses

```bash
expense-tracker list

ID  Date        Category   Description      Amount
--------------------------------------------------
1   2026-06-11  Food       Lunch            150 ETB
```

### Search Expenses

```bash
expense-tracker search Food
```

### Monthly Summary

```bash
expense-tracker summary 6

Total expenses for month 6: 150 ETB
```

---

## Learning Outcomes

Through this project I learned:

- Object-Oriented Programming in C++
- JSON data handling
- File operations in C++
- Command Line Interface development
- Data organization and management
- Real-world software development workflow

---

## Future Enhancements

- Monthly budget tracking
- Savings calculator
- Expense analytics dashboard
- Export reports to CSV
- Graphical User Interface (GUI)
- Expense charts and visualization
- User authentication system

---

## Author

Rakshita M N


GitHub:
https://github.com/Rakshita68

LinkedIn:
https://linkedin.com/in/rakshitamanjunath