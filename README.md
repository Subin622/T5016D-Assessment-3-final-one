# T5016D-Assessment-3-final-one


# Ticket Management System

Ticket Management System Overview. This Python script displays a basic ticket management system. It enables users to generate tickets for various requests or challenges, maintain records of the amount of tickets created and addressed, and print ticket data.

Features Ticket Creation: Users can create tickets with information such as the creator's name, staff ID, email address, and a description of the issue/request. Ticket Resolution: The ticket can be resolved automatically if a password change request is stated in the description. Otherwise, tickets may be resolved manually. Ticket Statistics: The system tracks the number of tickets created, resolved, and pending. Ticket Information: Users may print out full information on the purchased tickets.

Installation Python 3. x Download the repository to your local machine.

Usage Launch a program called terminal or command prompt. You can go to the folder where the script (ticket_management.py) is submitted. Run the script using Python 3. Python ticket_management.py

Instructions for Users When the script goes through execution, three ticket instances are immediately created with examples of data. Ticket descriptions with "Password Change" will be automatically managed with a generated password. To manually resolve a ticket, edit the response assets with the resolution information. Change the status of assets to "Pending" or "Closed" as required. Use the Ticket class' print_statistics() work to print ticket statistics. To print specific information about each ticket, use the print_ticket() function on the ticket object.

Contributors [Subin Shrestha]

License This project has been licensed under the MIT Licence; read the LICENCE file for additional information.










# Factorial Calculation

This Python software uses recursion to get the factorial of a given non-negative integer. It defines two functions: `main()` to receive user input and display the result, and `factorial(n)` to compute the factorial of a number {n}.


## Guidelines

Use this script by doing the following:

1. Installation: Verify that your computer is running Python. Python 3.x is required for this script.
2. Download: Use this repository to clone or download the `factorial_calculator.py` file.
3. Execution: Locate the script's directory by opening a terminal or command prompt.
4. Run Script: Use the following command to run the script:
5. Input: The script will ask you to input a number for which you wish to compute the factorial when it runs.
6. Output: Following that, the script will calculate and show the entered number's factorial.
7. Error Handling: The script will alert you if you enter a negative value because factorial is not specified for negative integers. The script will remind you to provide a valid integer if you enter a value that is not an integer.
8. Customisation: You may include the script into your own projects or make necessary modifications to it.
9. Contributing: We would appreciate your help! Please feel free to make modifications, send a pull request, and fork this repository.
10. Contact: Open an issue in this repository with any queries or problems.
11. Licence: The MIT Licence is used to distribute this script. Details may be found in the LICENCE file.

This script may be used to calculate factorials in a variety of applications and is a basic example of recursion in Python.















# To-Do List Organiser

This program written in Python uses the concepts of object-oriented programming to create a basic to-do list organizer. There are two classes in it: `Task` and `TodoList}. A single job is represented by the `job` class, which has properties such as name, description, and completion status. A collection of tasks is represented by the `TodoList` class, which includes methods for stating, marking as complete, and retrieving pending and finished tasks.


## Guidelines

Use this script by doing the following:

1. Installation: Verify that your computer is running Python. Python 3.x is required for this script.
2. Download: Use this repository to clone or download the `task.py` file.
3. Execution: Locate the script's directory by opening a terminal or command prompt.
4. Run Script: Use the following command to run the script:
5. Adding Tasks: By generating `Task} instances and adding them to the `TodoList} using the `add_task} function, the script enables you to add tasks to the to-do list.
6. Marking Tasks Complete: The `mark_task_complete} function accepts the task name as an argument and allows you to mark a task as complete.
7. Showing Tasks: The script will use the `get_pending_tasks` and `get_completed_tasks` methods to show pending and completed tasks, respectively, after adding tasks and marking them as complete.
8. Customisation: You may include the script in your projects or make necessary modifications to it.
9. Contributing: We would appreciate your help! Please feel free to make modifications, send a pull request, and fork this repository.
10. Contact: Open an issue in this repository with any queries or problems.
11. Licence: The MIT Licence is used to distribute this script. Details may be found in the LICENCE file.
    
This script serves as a simple example of how to use object-oriented programming ideas in Python to manage tasks inside a to-do list. It can serve as a basis for more intricate to-do list applications or help manage personal tasks.









