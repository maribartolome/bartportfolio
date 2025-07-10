# Debt Tracker Plan

How I visually tracked and planned my debt payments using Google Sheets.

# Debt Tracker Google Sheet Template

Keep track of your debts, payment plans, and remaining balances with this simple Google Sheets template.

---

## How to Set Up

1. **Open Google Sheets** and create a new spreadsheet.
2. **Create the following columns:**

| A              | B         | C             | D                  | E              |
|----------------|-----------|---------------|--------------------|----------------|
| Current Debts  | Amount    | Payment Plan  | Allocated Budget   | Remaining Debt |

---

## 1. Add Data Validation for Payment Plan

- Select cells in **Column C** (e.g., C2:C50).
- Go to **Data > Data validation**.
- For **Criteria**, select **Dropdown** or **List of items**.
- Enter: `Installment,Pay in Full`
- Click **Done**.

---

## 2. Enter Sample Data

| Current Debts | Amount | Payment Plan    | Allocated Budget | Remaining Debt |
|---------------|--------|----------------|------------------|---------------|
| Credit Card 1 | 10000  | Installment    | 2000             |               |
| Personal Loan | 50000  | Pay in Full    | 50000            |               |
| Credit Card 2 | 7000   | Installment    | 1000             |               |

---

## 3. Automate Remaining Debt Calculation

In cell **E2**, enter this formula and drag down:

```excel
=MAX(B2-D2, 0)
```

---

## 4. Add Totals

Below your data (e.g., row 10 if you have 8 debts):

- **B10 (Total Amount):**
  ```excel
  =SUM(B2:B9)
  ```
- **D10 (Total Allocated Budget):**
  ```excel
  =SUM(D2:D9)
  ```
- **E10 (Total Remaining Debt):**
  ```excel
  =SUM(E2:E9)
  ```

Style these total rows for clarity (e.g., bold them or use a different color).

---

## 5. Optional: Conditional Formatting

To highlight fully paid debts:

- Select **E2:E50**.
- Go to **Format > Conditional formatting**.
- Set the rule: **Format cells if** = `is equal to` **0**
- Choose a color (like green).
- Click **Done**.

---

## Final Table Example

| Current Debts | Amount | Payment Plan    | Allocated Budget | Remaining Debt |
|---------------|--------|----------------|------------------|---------------|
| Credit Card 1 | 10000  | Installment    | 2000             | 8000          |
| Personal Loan | 50000  | Pay in Full    | 50000            | 0             |
| Credit Card 2 | 7000   | Installment    | 1000             | 6000          |
| **Total**     | 67000  |                | 53000            | 14000         |

---

**Copy and customize this template in Google Sheets for your personal use!**
