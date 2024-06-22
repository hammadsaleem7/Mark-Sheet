# Mark-Sheet

This Python script is designed to create a student mark sheet by taking inputs for various subjects, calculating the total marks obtained, the percentage, and determining the grade based on the percentage. Here is a step-by-step description of the code:

Title and Input Prompt:

The code starts by printing a title for the mark sheet using print("Student Mark Sheet").
The user is then prompted to enter the student's name with name = input("Enter the student name ").
A line separator is printed for better visual clarity with print("==============================\n").
Input for Marks:

The user is prompted to enter marks for six subjects: English, Urdu, Maths, Science, Islamiat, and Computer.
Each subject's marks are input as integers using int(input("Enter [Subject] Marks ")).
Calculation of Total Marks and Percentage:

The total marks obtained by the student are calculated by summing the marks of all six subjects: Obtained_Marks = Eng + Urdu + Maths + Sci + Isl + Comp.
The total possible marks are defined as 600: Total_Marks = 600.
The percentage is then calculated using the formula: Percentage = (Obtained_Marks / Total_Marks) * 100.
Grade Determination and Congratulatory Message:

Based on the calculated percentage, the student's grade is determined using a series of if-elif-else statements:
If the percentage is 90 or above, an A grade message is printed.
If the percentage is 80-89, a B grade message is printed.
If the percentage is 70-79, a C grade message is printed.
If the percentage is 60-69, a D grade message is printed.
If the percentage is below 60, an F grade message is printed.
The message includes the student's name and is formatted using the format method.
Output of Percentage:

The student's percentage is printed with a message, again using the format method to include the student's name and the calculated percentage.
