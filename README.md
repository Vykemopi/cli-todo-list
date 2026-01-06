# Daily Task Manager (oT-oT)

A simple, type-safe Python CLI application for managing your daily tasks. Add, view, update, delete, search, and report on your todos. All from the terminal.

## Features

- Add new tasks with title, priority, and done status
- Prevents duplicate task titles
- View all tasks, sorted by priority (High → Low)
- Toggle task completion status
- Delete tasks
- Report: see counts of done/undone tasks
- Search tasks by keyword
- Robust input validation and error handling
- Type-safe code using `TypedDict` and type hints

## Getting Started

### Prerequisites

- Python 3.8 or newer

### Installation

Clone the repository:

```sh
git clone https://github.com/BaseMax/cli-todo-list.git
cd cli-todo-list
```

### Usage

Run the program in your terminal:

```sh
python lTCT.py
```

### Menu Options

```
--- Daily Task Manager (oT-oT) ---
1 - Add new task
2 - Show all tasks
3 - Toggle task status
4 - Delete a task
5 - Report (done/undone count)
6 - Search tasks
0 - Exit
```

### Example

```
Select an option (0-6): 1
Task title: Buy milk
Enter priority (1=High, 2=Medium, 3=Low): 1
Task added.
Select an option (0-6): 2
Tasks:
1. [ ] Buy milk (Priority: 1)
Select an option (0-6): 3
Enter task number to toggle: 1
Task status updated.
Select an option (0-6): 5
Done: 1 | Undone: 0
Select an option (0-6): 0
Exiting. Goodbye!
```

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

MIT License. Copyright (c) 2025 Seyyed Ali Mohammadiyeh (MAX BASE)

See [LICENSE](LICENSE) for details.
