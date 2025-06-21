# ✅ To-Do List Manager with File Persistence

A menu-driven **To-Do List Manager** built with Python that allows users to manage personal tasks, update their status, and store task data persistently in a file. This project focuses on **lists, functions, file I/O, and logical thinking**—ideal for beginner-to-intermediate learners.

---

## 🎯 Project Objectives

- Learn to use **lists of dictionaries** for structured data
- Design a **menu-based system** using loops and conditionals
- Practice **function modularity** and **file persistence**
- Apply **error handling** and **user input validation**
- Optionally add **timestamps**, **search**, and **custom export features**

---

## 🔧 Core Features

### 📌 Task Format

Each task is stored as a dictionary:
```python
{"id": 1, "task": "Buy groceries", "status": "Pending"}
````

### 🧾 Menu Options

```
=== TO-DO LIST MANAGER ===
1. Add New Task
2. View All Tasks
3. Update Task Status
4. Delete Task
5. Save Tasks to File
6. Load Tasks from File
7. Clear All Tasks
8. Exit
```

---

## ✅ Core Functionalities

1. **Add Task**

   * User enters task description
   * Auto-assigns a unique ID
   * Status defaults to `"Pending"`

2. **View Tasks**

   * Displays all tasks in a clean, readable table
   * Columns: ID | Task | Status

3. **Update Status**

   * User selects task ID to mark as `"Completed"` or `"Pending"`

4. **Delete Task**

   * Deletes a task by its ID
   * Handles non-existing ID gracefully

5. **Save Tasks to File**

   * Writes all tasks to `todo_list.txt` using `with` statement
   * File format is human-readable

6. **Load Tasks from File**

   * Loads tasks from file and rebuilds the internal task list
   * Prevents duplication and invalid format loading

7. **Clear All Tasks**

   * Prompts for confirmation
   * Clears in-memory task list for the session

8. **Exit**

   * Ends program cleanly

---

## 📁 Sample File Output

**Basic Format:**

```
ID: 1 | Task: Buy groceries | Status: Pending
ID: 2 | Task: Complete assignment | Status: Completed
```

**Bonus Format with Timestamp:**

```
ID: 3 | Task: Go jogging | Status: Pending | Added: 2025-06-21 08:12
```

---

## 💡 Bonus Challenges 

* ✅ **Timestamps**

  * Add `datetime.now()` to record when the task was added or completed

* ✅ **Search by Keyword**

  * Allow users to search for tasks containing specific words

* ✅ **Custom Export**

  * Save task list to a user-specified filename (e.g., `monday_tasks.txt`)

---

