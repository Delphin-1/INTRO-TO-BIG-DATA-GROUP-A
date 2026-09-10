# Week 1 Lab Report — Python Foundations
**Name:** Manzi Fred
**Student ID:** 26634
**Program:** Software Engineering
**Course:** Introduction to Big Data Analytics
**Instructor:** Prince Ishimwe
**Date:** September 10, 2026

---

## What I Built

In this lab I worked through a series of Python exercises designed to build the foundation
needed for Big Data analysis. Starting from basic variable declaration, I progressively
worked up to analyzing a real structured dataset of 20 AUCA students.

In **Part 1**, I created variables of four different types — string, integer, float, and
boolean — and practised type conversion by turning a text value into an integer to simulate
what happens when a dataset stores numbers as text, which is very common in real-world data.

In **Part 2**, I used f-strings to format output neatly and explored built-in string methods
such as `.upper()`, `len()`, and slicing. These are essential tools when cleaning and
inspecting text columns in a dataset.

In **Part 3**, I performed my first descriptive statistics on a list of quiz scores: finding
the first and last values, counting elements, computing the average, and identifying the
maximum and minimum. I also modified the list by appending a new score and correcting an
existing one, which mirrors real data-cleaning tasks.

In **Part 4**, I built a dictionary representing myself with labeled keys — a structure that
closely resembles one row in a database table or a JSON record from an API.

In **Part 5**, I analyzed a dataset of 20 AUCA students stored as a list of dictionaries.
I computed class-wide statistics (total count, average score of 77.2, highest score of 94,
lowest of 55, and a range of 39), inspected individual records, counted students per
district, and identified the top and bottom students by score — all without using any loops,
relying purely on built-in Python functions like `max()`, `min()`, and `.index()`.

---

## One Thing That Surprised Me

The most surprising thing was how `"3" + "4"` produces `"34"` instead of `7`. I expected
Python to add the numbers, but because the values were strings, the `+` operator
concatenated them instead of performing arithmetic. This made me realise that **data type
awareness is critical** in data analysis — if a numeric column is accidentally loaded as
text, every calculation on it will silently give wrong results. This is exactly why the type
conversion exercise in Part 1 matters so much in real Big Data pipelines.

---

*Submitted via GitHub branch: 26634_Manzi_fred_Assignment_1*
