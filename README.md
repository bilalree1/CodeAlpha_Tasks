# C++ Mini Projects Collection

## 📌 Overview

This repository contains two beginner-friendly C++ console applications designed to demonstrate fundamental programming concepts, file handling, and problem-solving techniques.

The projects included are:

1. **Student GPA Calculator**
2. **Login & Registration System**

Both projects are ideal for students and beginners who want to strengthen their understanding of C++ programming, user input handling, functions, loops, conditions, and file operations.

---

# 📚 Projects Included

## 1️⃣ Student GPA Calculator

### 📖 Description

The **Student GPA Calculator** is a console-based application developed in C++ that helps students calculate their GPA (Grade Point Average) based on subject grades and credit hours.

The program takes input for:

* Subject names
* Credit hours
* Obtained grades

It then calculates:

* Grade points
* Total credit hours
* Semester GPA

This project demonstrates the practical implementation of mathematical calculations and data processing using C++.

---

### ✨ Features

* Input multiple subjects
* Enter grades and credit hours
* Automatic GPA calculation
* User-friendly console interface
* Displays total GPA result
* Beginner-friendly logic implementation

---

### 🛠 Concepts Used

* Variables and Data Types
* Loops
* Conditional Statements
* Functions
* Arrays
* Mathematical Calculations
* User Input Handling

---

### 💻 Example Output

```bash
===== GPA CALCULATOR =====
Enter Number of Subjects: 3

Enter Subject Name: Programming
Enter Credit Hours: 3
Enter Grade: A

Enter Subject Name: Mathematics
Enter Credit Hours: 4
Enter Grade: B

Enter Subject Name: Physics
Enter Credit Hours: 3
Enter Grade: A

Your GPA is: 3.70
```

---

## 2️⃣ Login & Registration System

### 📖 Description

The **Login & Registration System** is a simple authentication application built in C++ using file handling.

Users can:

* Register a new account
* Log into an existing account
* Store credentials permanently in a text file

The system checks for duplicate usernames and validates login credentials during authentication.

This project helps beginners understand how user authentication systems work in real-world applications.

---

### ✨ Features

* User Registration
* User Login Authentication
* Duplicate Username Detection
* File-based Storage System
* Persistent User Data
* Console-based User Interface

---

### 🛠 Concepts Used

* File Handling (`ifstream`, `ofstream`)
* Functions
* Strings
* Loops
* Conditional Statements
* Authentication Logic
* Data Persistence

---

### 💻 Example Output

#### Registration

```bash
===== LOGIN & REGISTRATION SYSTEM =====
1. Register
2. Login
3. Exit
Enter Choice: 1

Enter Username: admin
Enter Password: 1234
Registration Successful!
```

#### Login

```bash
===== LOGIN & REGISTRATION SYSTEM =====
1. Register
2. Login
3. Exit
Enter Choice: 2

Enter Username: admin
Enter Password: 1234
Login Successful! Welcome admin
```

---

# 🛠 Technologies Used

* C++
* File Handling (`fstream`)
* Standard Input/Output
* Console-based Programming

---

# 📂 Repository Structure

```bash
├── GPA_CAl.cpp
├── codealpha_Login.cpp
├── users.txt
└── README.md
```

### File Details

| File Name             | Description                                 |
| --------------------- | ------------------------------------------- |
| `GPA_CAl.cpp`         | Source code for GPA Calculator              |
| `codealpha_Login.cpp` | Source code for Login & Registration System |
| `users.txt`           | Stores usernames and passwords              |
| `README.md`           | Project documentation                       |

---

# 🚀 How to Run the Projects

## 📌 Requirements

Make sure you have:

* A C++ compiler installed
* g++ (recommended)
* CodeBlocks / VS Code / Dev-C++ / Visual Studio

---

## ⚙️ Compilation Instructions

### Compile GPA Calculator

```bash
g++ GPA_CAl.cpp -o gpa_calculator
```

### Run GPA Calculator

```bash
./gpa_calculator
```

---

### Compile Login System

```bash
g++ codealpha_Login.cpp -o login_system
```

### Run Login System

```bash
./login_system
```

---

# 🎯 Learning Objectives

These projects help beginners learn:

* C++ syntax and structure
* Function creation and usage
* Input/output operations
* File handling in C++
* Authentication systems
* GPA calculation logic
* Loops and conditions
* Problem-solving skills

---

# 🔐 Security Note

The Login & Registration System stores passwords in plain text inside `users.txt`.

This project is intended for educational purposes only.

For real-world applications, passwords should be:

* Hashed
* Encrypted
* Stored securely in databases

---

# ⚠️ Limitations

## GPA Calculator

* Console-based only
* No graphical interface
* Limited grade validation

## Login System

* Passwords are not encrypted
* No password recovery feature
* No advanced validation
* Text-file based storage only

---

# 🌟 Future Improvements

Possible future upgrades include:

## GPA Calculator

* CGPA calculation support
* GUI interface
* Subject editing and deletion
* Grade history tracking

## Login System

* Password hashing
* Hidden password input
* Database integration
* Email verification
* Admin dashboard
* Multi-user roles

---

# 📖 Educational Value

These projects are excellent for:

* Beginner programmers
* C++ practice
* Academic mini-projects
* Programming assignments
* Learning file handling and calculations

---

# 🤝 Contribution

Contributions, suggestions, and improvements are welcome.

You can:

* Fork the repository
* Improve the code
* Add features
* Fix bugs
* Submit pull requests

---

# 📜 License

This project is open-source and available for educational and learning purposes.

---

# 👨‍💻 Author

Developed in C++ as part of learning and practice projects.
