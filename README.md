
---

# README.md

# INTRO-TO-BIG-DATA-GROUP-A - Assignment 1: Python Basics to Pandas Data Analysis

Student: Delphin 
Dataset: `week1_students.xlsx` - 20 student records



# PART I - II: Python Basics - Strings and Lists

# String Operations
1. upper() Method: Convert text to uppercase
   course_name = "Big Data Analytics".upper() # Output: BIG DATA ANALYTICS
2. len() Function: Get string length
   len("BIG DATA ANALYTICS") # Output: 18
3. Slicing: Extract part of a string
   course_name[0:3] # Output: BIG
# List Operations
List used: `score = [72][85][91][64][78]`
1. Access Elements: `score[0]` = 72, `score[-1]` = 78
2. len(): `len(score)` = 5
3. Statistics: `sum(score)/len(score)` = 78.0
4. max() / min(): Highest = 91, Lowest = 64
5. append(): `score.append(88)` → `[72][85][91][64][78][88]`
6. Modify: `score[3] = 66` → New Average = 80.0

# PART III - IV: Dictionaries

# Dictionary Operations
me = {"name":"Delphin", "age":22, "program":"IT", "District":"Gasabo"}
1. Access: `me["program"]` → `IT`
2. Add Key: `me["score"] = 18`
3. Update: `me["age"] = me["age"]+1` → `23`
4. Keys: `me.keys()` → `dict_keys(['name', 'age', 'program', 'District', 'score'])`

Dictionaries are useful for storing structured records with `key: value` pairs.

# PART V: Data Analysis with Pandas

Dataset loaded: `df = pd.read_excel("week1_students.xlsx")`

# 5.1 Basic Statistics
Metric | Value
Total Students | 20
Average Score | 77.2
Highest Score | 94
Lowest Score | 55
Score Range | 39
Code used:
len(df)
df['score'].mean()
df['score'].max()
df['score'].min()
# 5.2 Data Access and Filtering*
1. First/Last Row: `df.iloc[0]`, `df.iloc[-1]`
   - First: Aline Uwase, Information Systems, Score: 85
   - Last: Samuel Rukundo, Networking, Score: 92
2. Specific Student: `df.iloc[5]`
   - Patrick Mugisha from Huye studies Software Engineering and scored 83
3. Count by District:
   - Gasabo: 5, Kicukiro: 4, Rusizi: 1
   df[df["district"] == 'Gasabo'].shape[0]
4. Top Student:
   df['score'].idxmax()
→ Sandrine Umutoni with a score of 94
5. Lowest Student:
   df['score'].idxmin()
→ David Hakizimana with a score of 55

## PART VI: Reflection

1. Dataset Note: The dataset does not contain a "volume" column. Analysis focused on academic attributes.
2. Key Insight: 
   > I was surprised that we can find the best and the worst performing students without using loops
   
   Pandas vectorized functions like `.max()`, `.min()`, `.idxmax()` make analysis fast and efficient for Big Data, compared to manual `for` loops.

# Key Concepts Learned
1. Core Python: Strings, Lists, Dictionaries and built-in functions
2. Pandas: `read_excel()`, `head()`, `len()`, `mean()`, `max()`, `min()`
3. Data Access: `iloc[]` for row access, Boolean filtering for subsets
4. Efficiency: Vectorized operations replace loops for large datasets



---

