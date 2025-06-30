# 💸 Personal Expense Tracker (Python Console App)

A command-line tool to **track daily expenses**, **categorize spending**, and **monitor monthly budgets**. 
Ideal for personal use or learning Python file handling and CLI interaction.
---

## 🚀 Features

- 📆 Add daily expenses (with category and description)
- 📂 View all past expenses in a tabular format
- 📊 Set monthly budgets and track against actual spending
- 📤 Save and load data from CSV and JSON files
- ✅ User-friendly prompts and input validation
---

## 🛠️ Tech Stack

- Python 3.11
- Built-in modules: `csv`, `json`, `datetime`, `os`

---

## 📁 Project Structure

```
expense_tracker/
├── personal_expense_tracker.ipynb         # All logic in single file with classes
├── export/
│   └── full_file_personal_expense_tracker.pdf                     
│   └── screenshots_personal_expense_tracker.docx 
│   └── writeup_personal_expense_tracker.docx
├── data/
│   ├── expenses.csv                       # Saved expenses
│   └── budgets.json                       # Monthly budgets
├── README.md
```

---

## 🧑‍💻 Usage

Run the tracker:

```bash
python expense_app.py
```

### Example Flow:

```
💸 Hello from your Personal Expense Tracker!

1/A   Add expense
2/V   View expenses
3/T   Track budget
4/S   Save expenses
5/E   Exit
```

---

## 🙌 Acknowledgements

Built with ❤️ using Python and a lot of terminal inputs!