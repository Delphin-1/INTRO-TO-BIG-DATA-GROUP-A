# Week 3 Assignment – Student Data Analysis

A Python script that processes student grades and attendance data, calculates 
statistics, and generates a summary report. Built as a Week 3 assignment for 
AUCA Software Engineering coursework.

## What It Does

- **Grading**: Converts numeric scores into letter grades (A–F) using a grading scale
- **Validation**: Checks if a student passed based on score and attendance (≥50 score and ≥75% attendance)
- **List analysis**: Identifies top scorers and calculates pass/fail counts, totals, and averages from a list of scores
- **Savings calculator**: Estimates how many months it takes to save enough for a laptop given fixed monthly savings
- **CSV processing**: Reads `week3_students_3.csv`, a dataset of 40 AUCA students, and:
  - Extracts student names
  - Calculates the average score, skipping invalid entries (some records have `N/A` or `absent` instead of a number)
  - Finds the top-performing student and their grade
  - Groups students by district and finds the district with the highest average score
- **Report generation**: Writes a summary of the analysis to `week3_report.txt`

## Files

- `week3_eloge_mugisha.py` — main script (exported from Google Colab)
- `week3_students_3.csv` — input dataset: student_id, name, age, gender, program, district, attendance_pct, score
- `week3_report.txt` — generated output report

## How to Run

```bash
python week3_eloge_mugisha.py
```

You'll be prompted to enter marks and attendance percentage interactively. 
Make sure `week3_students_3.csv` is in the same folder before running.

## Requirements

- Python 3.x
- No external libraries — uses only Python's built-in functions

## Notes

- The script includes data validation: records where the score is missing or 
  non-numeric (e.g. `N/A`, `absent`) are counted as "bad" entries and excluded 
  from average calculations rather than crashing the program.
- A rule of thumb used here: if 20% or more of records are invalid, the dataset 
  should be corrected at the source rather than just skipped.

## Author

Eloge Mugisha
