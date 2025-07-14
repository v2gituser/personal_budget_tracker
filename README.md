# Personal Budget Tracker

A simple yet powerful Excel template for tracking your monthly income and expenses. It features an automated summary dashboard that provides a clear overview of your financial situation for any given month.

![Excel Tracker Screenshot](https://i.imgur.com/gOQYJ9k.png)

---

## Features

- **Automated Monthly Summary:** Get a real-time overview of your finances, including:
  - Previous Balance
  - Total Monthly Income
  - Total Monthly Expenses
  - Closing Balance
  - Expense-to-Income Ratio (%)
- **Dynamic Date Filtering:** Simply enter the year and month to instantly update the entire summary.
- **Smart Data Table:** The transaction log is an official Excel Table, which means it expands automatically. Just press `TAB` in the last cell to add a new row.
- **Conditional Formatting:** Expense amounts are automatically highlighted in red for easy visual scanning.
- **Robust Formulas:** Uses reliable Excel functions that work across different regional settings.

---

## How to Use

1.  **Download the File:** Download the `.xlsx` file from this repository.
2.  **Set the Year and Month:**
    - In cell `A1`, enter the **year** you want to view (e.g., `2025`).
    - In cell `B1`, enter the **month** you want to view (e.g., `July`).
    - The summary dashboard will update instantly.
3.  **Enter Your Transactions:**
    - Go to the `Transactions` table at the bottom.
    - **Date:** Enter the date of the transaction. **Important:** Ensure this is formatted as a real date in Excel.
    - **Income/Expenses:** Fill in *either* the `Income` column *or* the `Expenses` column with a description (e.g., "Monthly Salary", "Groceries").
    - **Amount:** Enter the corresponding amount. The font will automatically turn red for expenses.
    - **Remark:** Add any optional notes.
4.  **Add New Rows:** When you reach the last cell of the table, press the `TAB` key to automatically create a new, formatted row.

---

## Requirements

- Microsoft Excel (2013 or newer recommended for best compatibility with table functions).

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
