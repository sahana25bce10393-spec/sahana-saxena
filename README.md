# sahana-saxena
Overview of the Project
This project is a simple Python To-Do List application that is menu-driven. In a single execution session, the user can manage their tasks (add, view, and delete). Tasks are kept in an in-memory list (tasks), which is a temporary list that is not saved upon program termination. For illustrating basic Python concepts like lists, functions, loops, and conditional logic, it offers an easy-to-use, interactive command-line interface (CLI).
Important Features
Include Task (1): enables the user to add a new task to the list by entering it.

Delete Task (2): This function displays the current list and eliminates a task by using its numbered index.

Show Tasks (3): For clarity, all active tasks are shown, numbered.

The application loop is terminated by exit (4).
The algorithm
Until the user decides to quit, the program runs in an infinite loop (while True) that keeps asking for input.

Initialization: To store all of the things that need to be done, create an empty global list called tasks.

Start Main Loop: Initiate the ongoing user interaction loop.

Display Menu: Show the four choices (1-4).

Get Input: Examine the user's selection.

Selecting a Process:

Use tasks if '1' (Add Task): Requests a task string.To add it, use append().

If '2' (Delete Task):

Make use of the show_tasks() function.

Request a task number (num) if the list is not empty.

Verify the number; it must fall between 1 and len(tasks).

Use tasks.pop(num - 1) to remove the task if it is valid.

Call the show_tasks() function if '3' (Show Tasks) is selected.
If '4' (Exit): Use break to end the loop and print a farewell message.

If Other: If the input is incorrect, print an error.

Loop/Exit: Either finish the program or repeat step 3.

Designing from the Top Down
The project's logical structure divides the primary issue into smaller, modular functions and control flows.
