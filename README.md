Personal Expense Tracker
This Personal Expense Tracker program allows you to record and manage your expenses. It also tracks your monthly budget and provides a budget summary to help you manage your finances.

Features
Add Expense: Easily add an expense by specifying the amount, date, and category.
View Expenses: List all your expenses in a clear format, including the amount, date, and category.
Expense Summary: Get a summary of your total spending and breakdown of expenses by category.
Monthly Budget Tracking: Set a monthly budget and get a daily budget recommendation based on remaining days in the month.
Budget Persistence: Your monthly budget is saved to a file (budget.txt), so it's retained across sessions.
Prerequisites
Ensure you have Python 3.x installed on your system. No additional libraries are required for this program.

How to Run
Clone or download the program file to your local machine.
Open a terminal (or command prompt) and navigate to the folder containing the program.
Run the script using Python:
bash
Copy code
python expense_tracker.py
How to Use
Once the program is running, a menu will be displayed with the following options:

Add Expense: Allows you to add a new expense by specifying the amount, date, and category.
View Expenses: Displays a list of all recorded expenses, showing the amount, date, and category for each expense.
View Summary: Provides a summary of your total expenses and a breakdown of expenses by category.
View Budget Summary: Prompts you to set a monthly budget (if not already set), and provides a summary including:
Monthly budget
Total amount spent
Remaining budget
Number of days left in the month
Recommended daily budget based on the remaining balance
Exit: Exits the program.
Features in Detail
1. Add Expense
When you choose this option, the program will prompt you to enter:

Amount: The cost of the expense.
Date: The date of the expense in the format YYYY-MM-DD.
Category: The category of the expense (e.g., Food, Transport, Entertainment, etc.).
2. View Expenses
This option will display all recorded expenses in the format:

vbnet
Copy code
Amount: [amount], Date: [date], Category: [category]
3. View Summary
Provides a detailed report of:

Total Expenses: The sum of all your recorded expenses.
Expenses by Category: A breakdown of your spending by category, showing how much you've spent in each category.
4. View Budget Summary
This option tracks your monthly budget and displays:

The monthly budget you've set.
The total expenses so far.
The remaining balance for the current month.
The number of days left in the month.
A daily budget suggestion based on the remaining balance and days left.
If no budget is set, the program will prompt you to enter a monthly budget.

5. Exit
Exits the program and saves your monthly budget for the next session.

Data Persistence
Expenses: The expenses are not saved between sessions, but you can modify the program to store expenses in a file if needed.
Monthly Budget: The monthly budget is saved in budget.txt and automatically loaded the next time the program runs.
Future Enhancements
Expense Editing/Deletion: Add functionality to modify or delete existing expenses.
File Persistence: Store expenses in a CSV or text file to persist across sessions.
Graphs/Visualization: Integrate graphs to visualize expenses by category and over time.
Notifications: Add alerts when you’re close to exceeding your monthly budget.
