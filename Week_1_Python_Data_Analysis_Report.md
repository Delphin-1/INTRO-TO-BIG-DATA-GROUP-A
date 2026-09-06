# WEEK 1 PYTHON DATA ANALYSIS REPORT

## Introduction

This practical session introduced the fundamental concepts of Python programming and their application to basic data analysis. The work focused on variables, data types, type conversion, strings, lists, dictionaries, and extracting information from a student dataset. The exercises were completed using a dataset containing 20 AUCA students and their academic information.

## Objectives

The main objectives of the practical work were to:

- Understand and use Python's basic data types.
- Perform type conversion and string operations.
- Create, access, and modify lists and dictionaries.
- Extract information from structured student data.
- Calculate basic statistical values such as average, maximum, and minimum scores.
- Identify students based on their highest and lowest scores without using loops.

## Activities and Implementation

The practical began with creating variables representing a student's name, age, GPA, and attendance status. The `type()` function was used to identify the data type of each variable. Type conversion was then practiced by converting a string containing a number into an integer and performing arithmetic operations.

String manipulation was explored using methods such as `.upper()`, `len()`, and string slicing. Lists were used to store student scores, where elements were accessed, added, and modified. Basic calculations such as the average, highest score, and lowest score were also performed.

Dictionaries were introduced as a way of storing related information using key-value pairs. A student dataset containing 20 records was represented as a list of dictionaries. Information such as student names, scores, districts, programs, and attendance was extracted using list comprehensions.

The dataset was further analyzed to obtain summary statistics. The class contained **20 students**, with an average score of **76.5**, a highest score of **94**, and a lowest score of **55**. District frequencies were also calculated, showing that Gasabo had 5 students, Kicukiro had 4 students, and Musanze had 2 students.

Finally, the highest- and lowest-scoring students were identified without using loops. The `max()` and `min()` functions were combined with `.index()` to find the positions of the scores, which were then used to retrieve the corresponding student names and attendance information. The top student was **Sandrine Umutoni**, with a score of **94** and attendance of **97%**, while the lowest-scoring student was **David Hakizimana**, with a score of **55** and attendance of **72%**.

## Conclusion

The Week 1 practical provided a strong foundation in Python programming and basic data analysis. Through hands-on exercises, I learned how to work with different data types, manipulate strings, lists, and dictionaries, and extract meaningful information from a structured dataset. The exercises also demonstrated how Python's built-in functions can be combined to analyze data efficiently without always requiring loops. These skills provide an important foundation for more advanced data analysis and programming tasks.
