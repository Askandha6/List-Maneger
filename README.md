# List-Maneger
A simple command-line Python application that allows users to manage a to-do list by adding, viewing, marking as done, and removing tasks.

 Features

Add a new task

View all tasks

Mark tasks as completed

Remove tasks

Simple and interactive command-line interface

 Requirements

Python 3.x

No external libraries are needed.

 Setup & Run

Clone or Download the repository:

git clone https://github.com/your-username/todo-list-manager.git
cd todo-list-manager


Run the script:

python todo.py


Replace todo.py with the actual filename if it's different.
 Usage

After running the script, you'll be prompted with a menu:

===== To-Do List Manager =====
1. Add Task
2. View Tasks
3. Mark Task as Done
4. Remove Task
5. Quit


Choose an option by entering the corresponding number.

Follow the prompts to manage your tasks.

 Known Issues
 Fix Needed in Code:

There are a couple of bugs in your original code that should be corrected:

1. Constructor Typo

Replace:

def _init_(self):


with:

def __init__(self):

2. Incorrect if __name__ == "__main__" Syntax

Replace:

if _name_ == "_main_":


with:

if __name__ == "__main__":

3. Fix the print statement formatting

The multiline print should be:

print("\n===== To-Do List Manager =====")

 Example
===== To-Do List Manager =====
1. Add Task
2. View Tasks
3. Mark Task as Done
4. Remove Task
5. Quit
Enter your choice: 1
Enter the task: Buy groceries

Enter your choice: 2
1. Buy groceries

Enter your choice: 3
Enter the task number to mark as done: 1

Enter your choice: 2
1. Buy groceries (Done)

 License

This project is open-source and free to use for personal or educational purposes.

Let me know if you'd like a version of the code with the bug fixes included too.
