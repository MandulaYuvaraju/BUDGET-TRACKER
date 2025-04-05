# BUDGET-TRACKER
A simple web-based budget tracker application that helps users keep track of their income and expenses. This app allows users to add transactions, view a dynamic history, and calculate the overall balance. Transactions are stored locally in the browser, so your data persists across page reloads.

Features:-
Track Income and Expenses: Add both income and expense transactions with custom descriptions and amounts.

Dynamic Balance: Automatically updates the balance, income, and expenses when you add or remove transactions.

Transaction History: View a list of all added transactions with the option to delete any of them.

Data Persistence: All transactions are saved in the browser's local storage, ensuring data persistence across page reloads.

Responsive Design: The app is mobile-friendly and adjusts to different screen sizes.

Technologies Used:-
HTML: The structure of the webpage.

CSS: For styling the app, ensuring it is visually appealing and responsive.

JavaScript: Handles the logic of adding, removing, and updating transactions, as well as managing data in local storage.
Usage
Add a Transaction:

Enter a description for the transaction (e.g., "Salary", "Groceries").

Enter the amount. Positive values for income, and negative values for expenses.

Click on the "Add Transaction" button to add the transaction to the list.

View Transaction History:

Below the input fields, all your added transactions will be displayed.

Each transaction shows the description, amount, and a delete button (x).

Delete a Transaction:

To remove a transaction, click the "x" button next to the transaction. The balance and history will automatically update.

Balance, Income, and Expense Calculation:

The Balance will update automatically whenever a transaction is added or removed.

Income and Expense will also be updated based on your transactions.

Persistence:

The app uses localStorage to save your transactions. Even if you refresh the page or close the browser, your data will persist.

