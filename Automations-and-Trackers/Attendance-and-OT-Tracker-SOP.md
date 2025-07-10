# 📄 Standard Operating Procedure  
### Title: Attendance and OT Tracking Using Google Sheet

---

## 🟢 Purpose  
To ensure accurate recording of employee attendance, overtime hours, and leave usage while tracking banked hours for future time-off redemption.

---

## 📘 Scope  
Applies to all employees listed in the attendance tracker. Managed daily by the team lead or assigned administrator.

---

## 👥 Responsibilities  
- **Team Leads**: Input daily attendance and OT data  
- **Admin/Ops**: Reconcile redeemed hours and update bank hour summary  
- **Employees**: Inform leads of absences, OT, or leave plans

---

## 🛠 Tools Used  
- Google Sheets – Attendance and OT Tracker  
- Google Sheets data validation (dropdowns and formulas)  
- Optional: Google Apps Script for monthly reset automation

---

## 🔢 Procedure

### 1. Daily Attendance Logging
- Go to the correct date row in the tracker.
- For each employee:
  - Select **"Present"**, **"Absent"**, or **"On Leave"** from the dropdown.

### 2. Log Work Hours
- In the **Expected Work Hours** column, input default (usually 8 hours).
- Input **OT Hours** worked, if any.

### 3. OT Breakdown
- Fill in:
  - **Convert** – OT hours eligible to bank
  - **Approved** – Hours manually approved for payout or banking
  - **Redeemed** – Hours used against future leave
  - **Bank** – Remaining bankable hours (formula-based)

### 4. Monthly Bank Summary
- The summary table (top of the sheet) updates automatically:
  - **Total Converts**: OT converted to bank hours
  - **Redeemed**: Used hours
  - **Remaining Bank Hours**: Current usable balance

### 5. Leave Management
- If an employee uses banked time for leave:
  - Select **Leave Type** (e.g., Sick, Vacation)
  - Add **Start Date** and **End Date**
  - Redeemed hours should be reflected in the "Redeemed" column

### 6. Review Monthly
- At month-end:
  - Check the “Banked Hours” column per employee
  - Archive old data if needed
  - Prepare for next month (new date rows)

---

## 📝 Notes
- Any OT not approved is not bankable.
- Ensure redeemed hours match time-off durations.
- Encourage employees to use banked hours before expiration, if policy applies.