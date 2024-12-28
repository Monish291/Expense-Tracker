# Expense-Tracker
Expense Tracker is a simple and intuitive application designed to help individuals or businesses monitor and manage their finances by tracking their expenses and income. With this tool, you can easily categorize your transactions, set budgets, and visualize your financial trends to maintain control over your spending.
# Expense Tracker App

## Overview
The Expense Tracker App is a web application designed to help users efficiently track their expenses. The app provides a simple interface for adding, viewing, and deleting expenses while calculating the total amount dynamically.

## Features
- **Add Expenses:** Select a category, enter an amount, and specify the date of the expense.
- **View Expenses:** Display all added expenses in a table format with category, amount, and date columns.
- **Delete Expenses:** Remove individual expense entries.
- **Total Calculation:** Automatically updates the total expense amount when adding or deleting entries.

## Technologies Used
- **HTML**: Structure of the application.
- **CSS**: Styling for layout and design.
- **JavaScript**: Functionality and interactivity of the app.

## File Structure
```
expense-tracker-app/
├── index.html       # Main HTML file
├── style.css        # Styling for the app
├── script.js        # JavaScript for interactivity
└── README.md        # Project documentation
```

## How to Run the App
1. Clone the repository:
   ```bash
   git clone https://github.com/your-Monish291/Expense-Tracker-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd expense-tracker-app
   ```
3. Open `index.html` in your browser to view the application.

## How to Use
1. Fill out the input form:
   - Select a category (e.g., Food & Beverage, Rent, Transport).
   - Enter a valid amount (positive number).
   - Choose a date for the expense.
2. Click **Add** to add the expense to the table.
3. View all added expenses in the table below the input form.
4. To remove an expense, click the **Delete** button in the respective row.
5. The total amount is displayed at the bottom of the table and updates dynamically.

## Code Explanation

### HTML
The `index.html` file structures the app with:
- Input fields for category, amount, and date.
- A button to add expenses.
- A table to display the expense list and total amount.

### CSS
The `style.css` file styles the app:
- Centered headings and input form.
- Responsive table layout.
- Styled buttons for adding and deleting expenses.

### JavaScript
The `script.js` file adds functionality:
- Handles adding new expense entries.
- Dynamically updates the table and total amount.
- Implements deletion of individual rows and recalculates the total.

## Future Enhancements
- Add filtering options (e.g., by category or date).
- Enable data persistence with local storage or a database.
- Introduce advanced analytics, such as category-wise breakdowns.
- Enhance UI with animations and additional styling.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contributions
Contributions are welcome! Feel free to fork the repository, open an issue, or submit a pull request to suggest improvements.


