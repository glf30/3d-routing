# Finance Tracker Project

Create a small multi-page React application that allows a user to track simple financial transactions. A transaction should include an **id**, **type** (income or expense), **amount**, **category**, and **note**.

Each transaction should follow a basic structure:

```js
{
  id: number,
  type: "income" or "expense",
  amount: number,
  category: string,
  note: string
}
```

Your application should have multiple pages using React Router. At a minimum, include the following:

## Dashboard Page
Display summary information about the user’s finances. Show the **total income**, **total expenses**, and **overall balance** based on all transactions.

## Add Transaction Page
Create a page where the user can add a new transaction. The user should be able to enter the transaction details and add it to the main transaction list.

## Transactions List Page
Display all transactions in a list. Each item should show its key details.  
Include a way for the user to **filter** the list to show
  * Income, Expenses, or all
  * Transactions based on category  
Provide a way for the user to **delete** a transaction.

---

You may extend the app with additional features or styling, but the core functionality above should be included.
