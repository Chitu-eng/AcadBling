# AcadBling
Desktop expense tracker built with Python and wxPython featuring multi-window UI for entry, charts, and suggestions, CSV-backed storage, SIP calculator, multi-currency support, and optional PDF monthly expense reports. ​
```markdown
# Expense Tracker with SIP & PDF Reports

This repository contains a desktop expense tracker built in Python using wxPython, with three dedicated windows for expense entry, analytics (charts), and suggestions, plus an integrated SIP (Systematic Investment Plan) calculator and optional PDF report generation.[file:1] It was developed as a group project by a team of three members.[file:1]

## Features

- Multi-window GUI: Launcher, Entry, Charts, and Suggestions windows for seamless navigation.[file:1]
- Expense management: Add, edit, delete expenses with date, category, amount, currency, and notes, stored in `expenses.csv`.[file:1]
- Income tracking: Store month-wise income in `income.csv` for better budget context.[file:1]
- Analytics: Visualize income vs expenditure and top spending categories using embedded Matplotlib charts.[file:1]
- Suggestions: Monthly summary with income, expenses, balance, top categories, and rule-based saving/overspending tips.[file:1]
- SIP calculator: Estimate future corpus and required monthly SIP for a target amount.[file:1]
- Preferences: Configure preferred currency symbol and default monthly budget in `preferences.json`.[file:1]
- Reporting: Generate month-wise PDF expense reports with charts and top categories (or PNG + CSV fallback if PDF library is missing).[file:1]

## Requirements

- Python 3.8+ (recommended)[file:1]

### Python modules

Install the required modules with:

```bash
pip install wxPython matplotlib
```

Optional (for PDF reports):

```bash
pip install reportlab
```

Standard library modules used (no extra install needed): `csv`, `os`, `json`, `datetime`, `math`, `io`, `threading`, `sys`, `subprocess`, `collections`.[file:1]

## Setup & Usage

1. Clone this repository and navigate into the project folder.
2. Ensure the required modules are installed (see above).
3. Run the application:

   ```bash
   python JACKFRUIT_FINAL_2.py
   ```

4. Use the **Launcher** window to open:
   - **Entry Window**: Add expenses and set monthly income.
   - **Charts Window**: View income vs expenditure and category-wise charts.
   - **Suggestions Window**: See monthly summary, tips, start SIP, open preferences, or generate reports.[file:1]

The app will automatically create and update `expenses.csv`, `income.csv`, and `preferences.json` in the working directory as you use it.[file:1]

## Project Context

This project was built as a collaborative effort by a group of three students, focusing on designing a user-friendly **finance** dashboard with persistent storage, basic analytics, and report generation, all packaged in a desktop GUI application.[file:1]
```
