<h1 align="center">💸 Expense Tracker — Personal Finance App</h1>

<p align="center">
  A personal finance tracker built with pure Python in Jupyter Notebook.
  <br/>
  Track expenses, set budgets, and analyse spending — no libraries needed.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Level-Beginner-green?style=flat"/>
  <img src="https://img.shields.io/badge/Currency-INR%20₹-purple?style=flat"/>
</p>

---

## 📌 About

A beginner Python project that functions as a **personal expense tracker**.
Built using only Python fundamentals — lists, dictionaries, functions,
file handling, and f-strings. No pandas or external libraries required.

---

## ✨ Features

- ✅ Add expenses with date, category, description & amount
- 📋 View all expenses in a clean table format
- 📊 Spending breakdown by category with visual bars
- 💰 Set monthly budget & get over-budget alerts
- 📂 Filter expenses by category
- 🗑️ Delete specific expenses
- 💾 Save & load data from file (persists across sessions)

---

## 📊 Sample Output

📋 ALL EXPENSES:

Date         Category       Description        Amount

1    2026-05-01   Food           Breakfast & lunch  ₹120.00

2    2026-05-02   Study          Coursera sub       ₹800.00

3    2026-05-03   Transport      Bus pass           ₹200.00

                                       TOTAL    ₹1120.00
📊 SPENDING BY CATEGORY:

Study          ₹1299.00  █████ 46.2%

Food           ₹ 900.00  ████  32.0%

Transport      ₹ 200.00  █     7.1%

Shopping       ₹ 150.00  █     5.3%

---

## 🧠 Concepts Used

| Concept | Usage |
|---|---|
| Lists | Storing all expense records |
| Dictionaries | Each expense as a key-value record |
| Functions | Modular design — one function per feature |
| List comprehension | Filtering & summing expenses |
| for loop + enumerate | Displaying numbered tables |
| File handling | Save & load with open() |
| try / except | Handling missing file gracefully |
| global keyword | Updating budget across functions |
| sorted() + lambda | Sorting categories by amount |
| f-strings | All formatted output |

---

## 🚀 How to Run

1. Clone the repository
```bash
   git clone https://github.com/vishvi31/expense-tracker.git
```

2. Open `expense_tracker.ipynb` in **Jupyter Notebook**

3. Run cells in order:

| Cell | Action |
|---|---|
| Cell 1 | Setup — run once |
| Cell 2 | Load saved data |
| Cell 3 | Set monthly budget |
| Cell 4 | Add your expenses |
| Cell 5 | View all expenses |
| Cell 6 | Category breakdown |
| Cell 7 | Budget status |
| Cell 8 | Filter by category |
| Cell 9 | Delete an expense |
| Cell 10 | Save before closing |

---

## 📁 Project Structure

expense-tracker/
│
├── expense_tracker.ipynb   # Main Jupyter Notebook
├── expenses.txt            # Auto-generated when you save
└── README.md

---

## 👩‍💻 Author

**Vishvi** — Aspiring Data Scientist & AI Practitioner
📚 BA (Hons) English | Diploma in IT | IBM Data Science Certificate (Coursera)
🔗 [LinkedIn](https://www.linkedin.com/in/yourprofile) | [GitHub](https://github.com/vishvi31)

---

## 🌱 What's Next

- [ ] Add pandas for better data analysis
- [ ] Add matplotlib charts (pie chart, bar chart)
- [ ] Monthly summary reports
- [ ] Export to CSV
- [ ] Web version using Flask

---

<p align="center">Built with 💜 as part of my Python learning journey</p>
