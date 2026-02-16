# 📒 Contact Book CLI Application

## 📌 Project Overview

The **Contact Book CLI Application** is a Python-based command-line program that allows users to manage contacts efficiently. The application stores user details in a text file and supports operations like adding, viewing, searching, updating, and deleting contacts.

This project demonstrates fundamental programming concepts such as:

* File Handling
* Functions
* Loops
* Conditional Statements
* Error Handling
* Data Processing

---

## 🎯 Features

* Add new contacts
* View all contacts
* Search contacts by name or phone number
* Update existing contacts
* Delete contacts
* Persistent storage using text file

---

## 🛠 Technologies Used

* Python 3
* Text File Storage (`contacts.txt`)
* Command Line Interface (CLI)

---

## 📂 Project Structure

```
project-folder/
│
├── contact_book.py
├── contacts.txt
└── README.md
```

---

## ▶ How to Run the Program

### Step 1 — Install Python

Make sure Python is installed:

```
python --version
```

### Step 2 — Run Script

Navigate to project folder and run:

```
python contact_book.py
```

---

## 💾 Data Storage Format

Contacts are saved inside **contacts.txt** as comma-separated values:

```
Name,Phone,Email
John,9876543210,john@mail.com
Alice,9123456780,alice@mail.com
```

---

## 📖 Menu Options

```
1. Add Contact
2. View Contacts
3. Search Contact
4. Update Contact
5. Delete Contact
6. Exit
```

---

## ⚙ How It Works

* The program creates a file if it doesn't exist.
* Each contact is stored as one line in the file.
* When modifying data, the file is read, edited in memory, then rewritten.

---

## 🚀 Future Improvements

* GUI version using Tkinter
* Database storage (MySQL/SQLite)
* Import/Export contacts
* Password protection
* Sorting contacts

---

## 🎓 Learning Outcomes

Through this project, I learned:

* How file-based databases work
* Structuring modular Python programs
* Handling user input safely
* Designing CLI applications
* Debugging and testing logic

---

## 👨‍💻 Author

**Name:** *Shivaprasad Lakkukale*
**Project Type:** Python Internship Project
**Date:** *20-2-2026*

---

## 📜 License

This project is for educational purposes.
