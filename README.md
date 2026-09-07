      # Week 1 Lab — Python Foundations

     ## Introduction

      This repository contains my work for **Week 1 Lab — Python Foundations** in the *Introduction to Big Data Analytics* course at AUCA.

      The purpose of this assignment was to introduce the basic concepts of Python programming and show how Python can be used to work with data. During the          lab, I practiced variables, data types, type conversion, strings, lists, dictionaries, and basic analysis of a student dataset.

     The assignment also helped me understand the connection between Python programming and Big Data Analytics. The lab instructions required all exercises to       be completed in a Jupyter Notebook or Google Colab notebook named `Week1_YourName`.

     ---

     ## Objectives

    The main objectives of this lab were to:

* Understand basic Python variables and data types.
* Practice type conversion.
* Work with strings and f-strings.
* Create and modify Python lists.
* Calculate simple statistics using Python.
* Understand dictionaries and labeled data.
* Analyze a dataset containing 20 AUCA students.
* Use Python to find averages, minimums, maximums, and ranges.
* Count students according to their districts.
* Identify the student with the highest and lowest score.
* Understand why a small student dataset is not yet Big Data.

---

## Part 1: Variables and Data Types

In the first part of the assignment, I created four variables describing myself:

```python
my_name = "Alex"
my_age = 20
my_gpa = 3.7
am_i_present = True
```

I then used Python's `type()` function to check the data type of each variable.

The four data types used were:

* `str` — for text such as a name.
* `int` — for whole numbers such as age.
* `float` — for decimal numbers such as GPA.
* `bool` — for values that are either `True` or `False`.

This exercise helped me understand that Python variables can store different types of information.

---

## Part 2: Type Conversion

The next exercise demonstrated how data can sometimes be stored as text even when it represents a number.

For example:

```python
age_text = "21"
age = int(age_text)
age = age + 1
print(age)
```

The result is:

```text
22
```

I also learned that:

```python
print("3" + "4")
```

produces:

```text
34
```

instead of `7`. This happens because `"3"` and `"4"` are strings, so Python joins the two pieces of text together instead of performing numerical addition.

---

## Part 3: Strings

I practiced working with strings using the course name:

```python
course = "Big Data Analytics"
```

I used Python functions to:

1. Convert the text to uppercase.
2. Find the number of characters.
3. Get the first three characters.

For example:

```python
print(course.upper())
print(len(course))
print(course[0:3])
```

This part helped me understand how Python can be used to manipulate and examine text data.

---

## Part 4: Lists and Statistics

The assignment introduced lists using five quiz scores:

```python
scores = [72, 85, 91, 64, 78]
```

I practiced accessing the first and last values, counting the number of scores, and calculating basic statistics.

The original results were:

* First score: **72**
* Last score: **78**
* Number of scores: **5**
* Average: **78.0**
* Highest score: **91**
* Lowest score: **64**

I then modified the list by adding a new score of 88 and changing the fourth score from 64 to 66:

```python
scores.append(88)
scores[3] = 66
```

The updated list became:

```text
[72, 85, 91, 66, 78, 88]
```

The new average was **80.0**.

---

## Part 5: Dictionaries

I also learned about dictionaries, which are useful for storing information using labels or keys.

For example, a student can be represented using information such as:

```python
me = {
    "name": "Alex",
    "age": 20,
    "program": "Big Data Analytics",
    "district": "Gasabo"
}
```

I practiced accessing values using their keys and updating the dictionary by adding a score and increasing the age.

This helped me understand the difference between a simple list and labeled data stored in a dictionary.

---

## Part 6: Student Dataset Analysis

The main data analysis task used a dataset containing **20 AUCA students**. The dataset includes information such as student ID, name, age, gender, program, district, attendance percentage, and score.

I used Python to analyze the data and calculate basic descriptive statistics.

### Results

The analysis produced the following results:

| Analysis           | Result |
| ------------------ | -----: |
| Number of students |     20 |
| Average score      |   77.6 |
| Highest score      |     94 |
| Lowest score       |     55 |
| Score range        |     39 |

The student at **position 6** in the dataset was **Sandrine Umutoni**. She is from **Kicukiro**, studies **Information Systems**, and scored **94**.

The student with the highest score was also **Sandrine Umutoni**, with a score of **94**.

The student with the lowest score was **David Hakizimana**, with a score of **55**.

---

## District Analysis

I also counted students from different districts using Python's list `.count()` method.

The results were:

* **Gasabo:** 5 students
* **Kicukiro:** 4 students
* **Nyarugenge:** 3 students

This demonstrated how simple Python functions can be used to summarize information in a dataset.

---

## Big Data Reflection

The 20-student dataset is **not Big Data** because it is very small and can easily be stored and analyzed using a normal computer.

We discussed the five V's of Big Data:

1. **Volume**
2. **Velocity**
3. **Variety**
4. **Veracity**
5. **Value**

The dataset clearly does not have sufficient **Volume**, because it contains only 20 student records. It also does not demonstrate much **Velocity**, because the data is not being continuously generated or updated in real time.

The lab specifically asks students to reflect on whether the 20-student dataset qualifies as Big Data and which of the five V's it does not yet have.

---

## What I Learned

This lab helped me understand the foundations of Python and how programming can be applied to data analysis.

One thing that surprised me was how Python handles strings and numbers differently. For example:

```python
"3" + "4"
```

produces:

```text
"34"
```

rather than `7`.

This showed me why understanding data types is important when working with Python and datasets.

I also learned that even simple Python functions such as `sum()`, `len()`, `max()`, `min()`, and `.count()` can be useful for analyzing data.

---

## Conclusion

Overall, this lab gave me a basic understanding of Python programming and data analysis. I learned how to create variables, work with different data types, manipulate strings, create and modify lists, use dictionaries, and analyze a small student dataset.

The student dataset allowed me to apply these Python skills to a realistic example. I was able to calculate the class average, identify the highest and lowest scores, determine the score range, inspect individual student records, and count students by district.

This assignment provided a good foundation for future topics in **Big Data Analytics**, where larger and more complex datasets will require more advanced tools and techniques.

---

## Assignment Checklist

* [x] Python variables and data types
* [x] Type conversion
* [x] String manipulation
* [x] Lists and descriptive statistics
* [x] Dictionaries
* [x] Student dataset analysis
* [x] District counting
* [x] Top and lowest student analysis
* [x] Big Data reflection
* [x] Personal reflection
* [x] Report preparation

**Course:** Introduction to Big Data Analytics
**Assignment:** Week 1 Lab — Python Foundations
**Institution:** African Leadership University / AUCA
**Week:** 1

