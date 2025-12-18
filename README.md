Project Overview

This project is a command-line based To-Do List application developed using Python.
It allows users to manage daily tasks efficiently by providing features such as task creation, deadlines, persistent storage, completion tracking, and searching.

The project is designed especially for beginners to understand:

How real-world Python projects are structured

How data is stored and retrieved

How logic flows in an application

How to write clean, readable, and maintainable code

This project is suitable for:

Beginners in Python

Computer Science Engineering (AI) students

GitHub portfolios

University and internship applications

🎯 Objectives of the Project

The main goals of this project are:

To learn Python fundamentals through a practical application

To understand file handling using JSON

To implement CRUD operations (Create, Read, Update, Delete)

To practice user input validation

To learn how a real application saves data permanently

To build confidence in writing projects independently

🚀 Features (Explained in Detail)
➕ Add Tasks

Users can add a task description

Users can optionally add a deadline

Each task automatically stores:

Task name

Deadline

Completion status

Creation timestamp

👀 View Tasks

Displays all tasks in a numbered list

Shows:

Task name

Deadline (or “No deadline”)

Completion status (Done / Not Done)

Date and time when the task was added

✅ Mark Tasks as Completed

Users can select a task by its number

Task status changes from Not Done to Done

Completed tasks are clearly marked

❌ Delete Tasks

Users can delete a specific task using its number

Prevents invalid task numbers using input validation

🔍 Search Tasks

Users can search tasks using keywords

Searches through:

Task names

Deadlines

Displays matching results only

🧹 Clear All Tasks

Allows users to delete all tasks at once

Includes confirmation to prevent accidental deletion

💾 Persistent Storage

Tasks are saved in a file called tasks.json

Data remains even after closing the program

Automatically loads saved tasks on startup

🎨 Colored Terminal Output (Optional)

Uses the colorama library

Makes the app visually appealing

If colorama is not installed, the app still works normally

🛠️ Technologies Used
Technology	Purpose
Python 3	Core programming language
JSON	Store tasks permanently
OS Module	File existence checking
datetime	Timestamping tasks
colorama (optional)	Colored terminal output
