This will be the guide for the actual code.
=

*# Simple Grade Calculator*
*# This program calculates the average grade of a student*
*# and assigns a corresponding letter grade.*

*# Ask the user for grades in different subjects*
math = float(input("Enter Math grade: "))
science = float(input("Enter Science grade: "))
english = float(input("Enter English grade: "))

*# Calculate the average of the grades*
average = (math + science + english) / 3

*# Display the average, rounded to 2 decimal places*
print("\nAverage:", round(average, 2))

*# Determine the letter grade based on the average*
if average >= 90:
    print("Grade: A")
elif average >= 80:
    print("Grade: B")
elif average >= 70:
    print("Grade: C")
elif average >= 60:
    print("Grade: D")
else:
    print("Grade: F")
