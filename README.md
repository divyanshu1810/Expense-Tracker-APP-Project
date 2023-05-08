## Expense Tracker
This is a simple expense tracker application built using Python's tkinter GUI toolkit and sqlite3 database module. The application allows users to keep track of their daily expenses by adding and viewing transactions.

### Features
Add new transactions with a title, amount, and date.
View all transactions in a table.
Delete transactions by selecting them in the table.

### Requirements
Python 3.x
tkinter module (should be included with Python)
sqlite3 module (should be included with Python)
### Usage
To run the application, simply execute the ```app.py``` script:

The main window will open, and you can start adding transactions by clicking the "Add Transaction" button. To view existing transactions, click the "View Transactions" button. To delete a transaction, select it in the table and click the "Delete" button.

### Database
The application uses a SQLite database to store transactions. The database is created automatically when you run the application for the first time, and it is saved as a file named expenses.db in the same directory as the expense_tracker.py script.

The database has a single table named transactions with the following columns:

id (integer, primary key): unique identifier for each transaction
title (text): title of the transaction
amount (real): amount of the transaction
date (text): date of the transaction in the format "YYYY-MM-DD"
Limitations
This expense tracker is a simple application and has some limitations:

No authentication or security features.
No data validation or error handling.
No filtering or sorting of transactions in the table.
No charts or graphs to visualize expenses.
### Contributions
Contributions to this project are welcome! Feel free to open a pull request with any improvements or features you would like to add.

### License
This project is licensed under the MIT License.
