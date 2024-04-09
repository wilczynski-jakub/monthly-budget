# Monthly Budget
Control your finances! Plan how much to spend on each category, and then track your expenses throughout the month.

## [monthly-budget-template.xlsx](monthly-budget-template.xlsx)
| Cell | Functionality |
|-------|------|
| ![Screenshot 1](screenshots/1.png) | The first sheet: "TRANSACTIONS". |
| ![Screenshot 2](screenshots/2.png) | Here you should be pasting the .csv data from your bank account's transaction history. Unnecessary data should land in the hidden columns (B, D-G, I-K). |
| ![Screenshot 3](screenshots/3.png) | Transactions' categories column: the data in another sheet will be grouped by these categories. Most banks are categorizing transactions automatically, however, you might consider your own modifications. |
| ![Screenshot 4](screenshots/4.png) | Assuming your bank uses a "DD.MM..." date format, the formulas in this column will retrieve only the day number of each transaction (needed for grouping them in another sheet by the week). |
| ![Screenshot 5](screenshots/5.png) | This column will contain a unique list of all categories - without repetitions. |
| ![Screenshot 6](screenshots/6.png) | The second sheet: "THE EXPENSES TABLE". This is how it will look like after pasting a list of transactions in the first sheet. |
| ![Screenshot 7](screenshots/7.png) | A comparison diagram: budgeted costs versus executed costs. |
