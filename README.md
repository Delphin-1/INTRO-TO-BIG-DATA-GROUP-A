Week 1 Lab — Python Foundations
This lab was my first real pass at Python — variables, strings, lists, dictionaries — building up to analyzing a small class dataset of 20 AUCA students (week1_students.csv). It's less about tricky logic and more about getting comfortable with the basics I'll be leaning on for the rest of the course.

What I submitted
My notebook, renamed Week1_YourName, with every exercise in its own cell and everything running clean
A short write-up (½–1 page) describing what I built and one thing that surprised me
Screenshots of the running code
Answers to the reflection questions below
Walking through the parts
Part 0 — Warm-Up (not graded) Just made sure the notebook worked: renamed it and printed "Hello, Big Data!".

Part 1 — Variables & Data Types (5 marks) Created four variables about myself — my_name (str), my_age (int), my_gpa (float), am_i_present (bool) — and printed each one with its type. Then took age_text = "21", a number stored as text, converted it to an int, and added 1 for a birthday. Also had to run "3" + "4" and explain in a sentence why that gives "34" instead of 7 — string concatenation, not addition.

Part 2 — Strings (5 marks) Used an f-string to combine my Part 1 variables into one sentence: "I am NAME, AGE years old, studying at AUCA." Then, given course = "Big Data Analytics", printed it in uppercase, counted its characters with len(), and sliced out the first 3 characters.

Part 3 — Lists & First Descriptive Statistics (7 marks) Given scores = [72, 85, 91, 64, 78], pulled the first and last score, counted them, worked out the average, and found the max and min. Then updated the list — appended a new score of 88, fixed a wrong value at position 3, and recalculated the average.

Part 4 — Dictionaries (5 marks) Built a dictionary called me with "name", "age", "program", "district" as keys, and printed my program with me["program"]. Then added a "score" key, bumped "age" up by 1, and printed all the keys plus the full dictionary.

Part 5 — Class Dataset Analysis (13 marks) This was the biggest part — working with all 20 students from week1_students.csv via list comprehensions (names, all_scores, districts). Printed class size, average score, highest/lowest score, and the range. Pulled the full record for the first and last student, plus a one-line summary for the student at position 6. Counted students by district (Gasabo, Kicukiro, and one more of my choice) using .count(). For the stretch goal, found the top student with no loop at all — just max(), .index(), and list lookup — and for the bonus, did the same for the lowest scorer, including attendance.

My results
Class average score: ___
Highest / lowest score: ___
Range: ___
Top student (name & score): ___
Lowest student & bonus attendance figures: ___
District counts (Gasabo / Kicukiro / other): ___
Reflection
Is this 20-student dataset actually Big Data? Which of the 5 V's is it clearly missing, and why?
One thing from this session that surprised or confused me: ___

