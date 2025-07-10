# 🕒 Attendance and OT Tracker

This tracker is designed to manage and monitor **daily attendance**, **overtime hours**, and **leave balances** for team members. It includes features to convert OT to banked hours, redeem hours for time off, and view real-time leave usage. 

Here's the link: https://docs.google.com/spreadsheets/d/1qkhF7kVk6tI6m1aqa1WdI3ABI7CA_sjAUrWii9CL7sY/edit?usp=sharing

Simply make a copy and customize it according to your needs!

---

## 📌 Features

### ✅ Attendance Monitoring
- Daily attendance dropdown: `Present`, `Absent`, `On Leave`
- Automatically tracks attendance per employee per day

### ⏱️ Overtime Tracking
- Logs expected work hours and actual OT
- Supports conversion of OT hours into:
  - **Converted hours** (for redemption)
  - **Approved hours**
  - **Banked hours** (for future leave usage)
  - **Redeemed hours** (already used)
- Overtime breakdown is color-coded for clarity

### 💼 Monthly Bank Hours
- Table summary at the top shows:
  - Total OT converted to hours
  - Redeemed hours
  - Remaining banked hours

### 🌴 Leave Management
- Supports entry of:
  - **Leave type** (e.g. Sick, Vacation, Emergency)
  - **Start and end dates**
- Calculates impact of redeemed hours and leave days

---

## 🧮 How It Works

1. **Log Attendance**  
   Select each employee’s daily attendance status from the dropdown.

2. **Input OT Hours**  
   Enter actual OT hours worked, how many were converted, approved, and redeemed. The rest will be banked.

3. **Bank Hours Summary**  
   The top summary updates the totals of converted, redeemed, and banked hours per employee monthly.

4. **Manage Leaves**  
   Use the dropdowns to select leave types and record date ranges when leaves are applied. Redeemed hours reduce from the bank.

---

## 🔄 Suggested Automations (optional)
- Conditional formatting for flagged entries (e.g., unapproved OT)
- Data validation for leave types
- Monthly rollover script for clearing used hours
- Pivot summary of total OT and attendance compliance

---

## 👤 Sample Employees
- Apple Doe
- Strawberry Doe
- Cherry Doe
- John Doe
- Banana Doe

---

## 📂 File Format
This tracker is currently maintained in **Google Sheets** with dropdowns, formulas, and conditional formatting.

If you'd like the actual spreadsheet template or a Google Apps Script version, I can provide that too!
