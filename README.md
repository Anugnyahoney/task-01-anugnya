# 📝 To-Do List Application

## 📌 Project Overview

This is a simple command-line **To-Do List Application** built using Python. The program allows users to manage their daily tasks by adding, viewing, searching, and removing tasks through an interactive menu.

This project is part of **DecodeLabs Project 1** and is designed to demonstrate the use of Python fundamentals such as:

* Functions
* Lists
* Dictionaries
* Loops
* Conditional Statements
* Exception Handling
* User Input

---

## 🚀 Features

### ✅ Add Task

Allows users to add a new task to the to-do list.

### 📂 View Tasks

Displays all tasks along with their unique IDs.

### 🔍 Search Task

Searches tasks based on a keyword entered by the user.

### 🗑 Remove Task

Removes a task using its Task ID.

### 👋 Exit Program

Safely exits the application.

---

## 📁 Project Structure

```text
todo_list.py
README.md
```

---

## ⚙️ Requirements

* Python 3.x

Check Python version:

```bash
python --version
```

---

## ▶️ How to Run

1. Clone or download the project.

2. Open a terminal in the project folder.

3. Run the Python file:

```bash
python todo_list.py
```

---

## 💻 Sample Output

```text
======================
   TO-DO LIST MENU
======================

1. Add Task
2. View Tasks
3. Search Task
4. Remove Task
5. Exit

Enter your choice: 1

Enter task title: Complete Python Project
✅ Task Added Successfully!
```

---

## 📖 How It Works

### Task Storage

Tasks are stored in a Python list:

```python
tasks = []
```

Each task is represented as a dictionary:

```python
{
    "id": 1,
    "title": "Complete Python Project"
}
```

### Task IDs

A unique Task ID is automatically assigned to each task using:

```python
task_id = 1
```

The ID increments whenever a new task is added.

---

## 🛠 Functions Used

| Function        | Description                  |
| --------------- | ---------------------------- |
| `add_task()`    | Adds a new task              |
| `view_tasks()`  | Displays all tasks           |
| `search_task()` | Searches tasks by keyword    |
| `remove_task()` | Deletes a task using Task ID |

---

## 🔒 Error Handling

The application handles invalid inputs while removing tasks:

```python
except ValueError:
    print("⚠ Please enter a valid number.")
```

This prevents the program from crashing if the user enters non-numeric data.

---

## 🎯 Learning Outcomes

By completing this project, you will understand:

* List operations
* Dictionary usage
* Function creation
* Loop control
* User interaction in terminal applications
* Basic exception handling


