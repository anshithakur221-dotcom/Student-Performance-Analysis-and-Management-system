# Student Performance Management and Data Analysis System

A beginner-friendly MCA Python project demonstrating core Python, OOP, NumPy, Pandas, Matplotlib, Seaborn, and Tkinter.

## Features
- Add, view, update, delete, and search student records
- Validate marks (0-100) and prevent duplicate roll numbers
- Calculate total, percentage, and grade
- Display class statistics using NumPy
- Build a Pandas DataFrame and export records to CSV
- Visualize subject averages, grade distribution, student marks, and correlations
- Demonstrate inheritance and polymorphism with student subclasses
- Handle missing subject marks in records

## Requirements
- Python 3.10 or newer recommended
- Tkinter (usually included with Python on Windows)
- Libraries listed in `requirements.txt`

## Setup (Windows)
1. Extract the ZIP folder.
2. Open the folder in VS Code.
3. Open Terminal > New Terminal.
4. Install dependencies:
   ```bash
   python -m pip install -r requirements.txt
   ```
5. Start the application:
   ```bash
   python main.py
   ```

If `python` does not work on Windows, try `py` instead:
```bash
py -m pip install -r requirements.txt
py main.py
```

## First run
- Click **Import Demo Data** to load sample records.
- Select a row to put its information into the form.
- Use **Update Selected** or **Delete Selected** to manage that record.
- Click **Class Statistics** to view class-level statistics.
- Use the graph buttons to open charts.
- Click **Export CSV** to save the table as a CSV file.

## Grade scheme used
- 90% and above: A+
- 80–89.99%: A
- 70–79.99%: B
- 60–69.99%: C
- 40–59.99%: D
- Below 40%: F

Percentage is calculated from the marks entered (ignoring blank/missing subjects). This makes partial records comparable only with care; enter all subjects for official results.

## Important academic note
The demo records are fictional sample data. Replace them with permitted data for your submission. This project stores records in memory while it is running; export to CSV before closing if you need to keep the data.
