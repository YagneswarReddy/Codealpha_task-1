# Codealpha_task-1

Overview of the Code
The provided Java program, StudentGrades, is designed to manage and analyze student grades. It performs several
 tasks such as collecting grades from the user, determining the highest and lowest grades, calculating the class 
average, and printing the results. Here's a breakdown of its main components and functionality:
Main Method:

Initializes a Scanner object for user input.
Collects the number of students using getNumberOfStudents.
Retrieves grades for each student using getGrades.
Finds the student with the highest grade using findHighestGradeStudent.
Finds the student with the lowest grade using findLowestGradeStudent.
Calculates the class average using calculateAverage.
Prints the results using printResults.
getNumberOfStudents Method:

Prompts the user to enter the number of students.
Ensures the number of students is positive by validating the input.
getGrades Method:

Prompts the user to enter grades for each student.
Ensures grades are between 0 and 100 by validating the input.
Stores each student’s grade in an array of Student objects.
getGradesAsArray Method:

Converts the array of Student objects to an array of integers containing only the grades.
calculateAverage Method:

Calculates the average grade from an array of grades.
findHighestGradeStudent Method:

Iterates through the array of students to find the one with the highest grade.
findLowestGradeStudent Method:

Iterates through the array of students to find the one with the lowest grade.
