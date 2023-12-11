# Python-Numpy-Checkpoint
#NUMPY CHECKPOINT
#Create a numpy array called "grades" that contains the following grades: [85, 90, 88, 92, 95, 80, 75, 98, 89, 83]
import numpy as np
grades = np.array([85, 90, 88, 92, 95, 80, 75, 98, 89, 83])
# Print the array
print("Grades:", grades)
 #instructions:

#grades_analysis.py:
import numpy as np

# Create the "grades" array
grades = np.array([85, 90, 88, 92, 95, 80, 75, 98, 89, 83])

# Calculate mean, median, and standard deviation
mean_grade = np.mean(grades)
median_grade = np.median(grades)
std_deviation = np.std(grades)

# Print the results
print("Grades:", grades)
print("Mean:", mean_grade)
print("Median:", median_grade)
print("Standard Deviation:", std_deviation)

import numpy as np
# Create the "grades" array
grades = np.array([85, 90, 88, 92, 95, 80, 75, 98, 89, 83])
# Calculate maximum and minimum grades
max_grade = np.max(grades)
min_grade = np.min(grades)
# Sort grades in ascending order
sorted_grades = np.sort(grades)
# Find the index of the highest grade
index_of_highest_grade = np.argmax(grades)
# Count the number of students who scored above 90
num_students_above_90 = np.sum(grades > 90)
# Print the results
print("Grades:", grades)
print("Maximum Grade:", max_grade)
print("Minimum Grade:", min_grade)
print("Sorted Grades:", sorted_grades)
print("Index of Highest Grade:", index_of_highest_grade)
print("Number of Students Above 90:", num_students_above_90)


# Create the "grades" array
grades = np.array([85, 90, 88, 92, 95, 80, 75, 98, 89, 83])

# Calculate the percentage of students who scored above 90
percentage_above_90 = np.mean(grades > 90) * 100

# Calculate the percentage of students who scored below 75
percentage_below_75 = np.mean(grades < 75) * 100

# Extract all grades above 90 into a new array "high_performers"
high_performers = grades[grades > 90]

# Create a new array "passing_grades" containing grades above 75
passing_grades = grades[grades > 75]

# Print the results
print("Grades:", grades)
print("Percentage of Students Above 90:", percentage_above_90, "%")
print("Percentage of Students Below 75:", percentage_below_75, "%")
print("High Performers:", high_performers)
print("Passing Grades:", passing_grades)
