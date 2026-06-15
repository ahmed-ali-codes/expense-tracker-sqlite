# 💰 Expense Tracker with SQLite

A Python command-line application for managing and tracking personal expenses. Data is stored persistently using a local **SQLite** database, with reporting and CSV export powered by **pandas**.

![Python](https://img.shields.io/badge/Python-3.7%2B-blue?logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-Database-lightgrey?logo=sqlite&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

---

## ✨ Features

- **SQLite Database Integration** — Expenses are saved persistently using a local `.db` file via Python's built-in `sqlite3` module.
- **Object-Oriented Design** — Clean architecture using an `ExpenseTracker` class for modularity and maintainability.
- **Full CRUD Operations** — Create, Read, Update, and Delete expenses with ease.
- **Expense Categorization** — Classify transactions by category (e.g., Food, Transport, Utilities, Entertainment).
- **Monthly Reports** — Generate detailed monthly breakdowns summarized by category with totals.
- **CSV Export** — Export your full expense history to a `.csv` file for use in Excel or Google Sheets.
- **Input Validation** — Robust error handling for date formats, numeric amounts, and invalid IDs.

---

## 📋 Prerequisites

- Python 3.7+
- `pandas` library

---

## 🚀 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ahmed-ali-codes/expense-tracker-sqlite.git
   cd expense-tracker-sqlite
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

---

## ▶️ Usage

Run the application from your terminal:

```bash
python expense_tracker.py
```

### 📌 Menu Options

| Option | Description |
|--------|-------------|
| 1. Add Expense | Add a new transaction (date, category, description, amount) |
| 2. View All Expenses | Display a formatted table of all recorded expenses |
| 3. Update Expense | Edit an existing expense by its ID |
| 4. Delete Expense | Remove an expense by its ID |
| 5. Generate Monthly Report | View a category-wise summary for a chosen month/year |
| 6. Export to CSV | Export all expense data to a `.csv` file |
| 7. Exit | Safely close the database connection and quit |

---

## 🗂️ Project Structure

```
expense-tracker-sqlite/
├── expense_tracker.py   # Main application with ExpenseTracker class and CLI
├── requirements.txt     # Python dependencies
├── .gitignore           # Git ignore rules (excludes .db and .csv files)
└── README.md            # Project documentation
```

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python 3 | Core programming language |
| `sqlite3` | Built-in database engine for persistent storage |
| `pandas` | Data analysis, display, and CSV export |

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
