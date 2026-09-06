 INTRODUCTION TO BIG DATA ANALYTICS
WORK
Name: NGARUKIYE NGABO JOEL 
ID:29145

Part 0 : Warm-Up
Exercise 0.1 : Hello, Big Data!
print("Hello, Big Data!")
Part 1 : Variables & Data Types
Exercise 1.1 : Variables and Data Types
my_name = "Joel"
my_age = 22
my_gpa = 3.5
am_i_present = True

print(my_name, type(my_name))
print(my_age, type(my_age))
print(my_gpa, type(my_gpa))
print(am_i_present, type(am_i_present))
Exercise 1.2 : Convert Text to Integer
age_text = "21"

age = int(age_text)
age = age + 1

print(age)
Question 1.3 : Why is "3" + "4" not 7?
print("3" + "4")
Explanation: "3" and "4" are strings (text), so Python joins them together and produces 34 instead of adding them as numbers.
Part 2 :Strings
Exercise 2.1 : F-String
print(f"I am {my_name}, {my_age} years old, studying at AUCA.")
Exercise 2.2 : String Operations
course = "Big Data Analytics"

print(course.upper())
print(len(course))
print(course[0:3])
Part 3 :Lists
Exercise 3.1 : Analyze Scores
scores = [72, 85, 91, 64, 78]

print("First score:", scores[0])
print("Last score:", scores[-1])
print("Number of scores:", len(scores))
print("Average:", sum(scores) / len(scores))
print("Highest score:", max(scores))
print("Lowest score:", min(scores))
Exercise 3.2 : Update the List
scores = [72, 85, 91, 64, 78]

scores.append(88)
scores[3] = 66

print("Updated list:", scores)
print("New average:", sum(scores) / len(scores))
Part 4 :Dictionaries
Exercise 4.1 : Create Your Dictionary
me = {
    "name": "Joel",
    "age": 22,
    "program": "Software Engineering",
    "district": "Gasabo"
}

print(me["program"])
Exercise 4.2 :Add and Update Information
me = {
    "name": "Joel",
    "age": 22,
    "program": "Software Engineering",
    "district": "Gasabo"
}

me["score"] = 85
me["age"] = me["age"] + 1

print(me.keys())
print(me)
Part 5 : Class Dataset Analysis
Exercise 5.1 : Class Description
# CLASS DESCRIPTION

print(f"Number of students: {len(students)}")
print(f"Class average score: {round(sum(all_scores) / len(all_scores), 1)}")
print(f"Highest score: {max(all_scores)}")
print(f"Lowest score: {min(all_scores)}")
print(f"Score range: {max(all_scores) - min(all_scores)}")
Exercise 5.2 : First, Last, and Position 6
# FIRST, LAST, AND POSITION 6

print("First student:", students[0])
print("Last student:", students[-1])

student = students[6]

print(f"{student['name']} from {student['district']} studies {student['program']} and scored {student['score']}.")
Exercise 5.3 : District Counts
# DISTRICT COUNTS

print("Gasabo:", districts.count("Gasabo"))
print("Kicukiro:", districts.count("Kicukiro"))
print("Nyarugenge:", districts.count("Nyarugenge"))
Exercise 5.4 : Top Student
# TOP STUDENT

top_score = max(all_scores)
top_index = all_scores.index(top_score)
top_student = students[top_index]

print("Top student:", top_student["name"])
print("Score:", top_student["score"])
Bonus :Lowest Student
# LOWEST STUDENT

lowest_score = min(all_scores)
lowest_index = all_scores.index(lowest_score)
lowest_student = students[lowest_index]

print("Lowest student:", lowest_student["name"])
print("Score:", lowest_student["score"])
print("Attendance:", lowest_student["attendance"])
Part 6 : Reflection
Q 1
No, this 20-student dataset is not Big Data because it is too small. It clearly does not have high Volume, since there are only 20 student records.
Q 2
I was surprised by how Python can easily calculate the average, highest score, lowest score, and other information from a dataset using simple functions.

