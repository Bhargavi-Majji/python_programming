# Python Programming 

# Task 1: Hello World Program
## 1. Problem Statement

Write a Python program to display the message "Hello World" on the screen.

## 2. Algorithm
Start
Display the message "Hello World"
Stop
## 3. Flowchart

Start → Display "Hello World" → Stop

## 4. Python Source Code
```python
print("Hello World")
```
## 5. Sample Input/Output

Output:
Hello World

# Task 2: Personal Information Display

## 1. Problem Statement
Write a Python program to display a student's personal information including name, roll number, branch, and college name.

## 2. Algorithm
1. Start
2. Store student details
3. Display student details
4. Stop

## 3. Flowchart
Start → Store Student Details → Display Details → Stop

## 4. Python Source Code

```python
name = "Bhargavi"
roll_no = "12345"
branch = "ECE"
college = "NRI Institute of Technology"

print("Name:", name)
print("Roll Number:", roll_no)
print("Branch:", branch)
print("College:", college)
```
## Output:
```python
Name: Bhargavi
Roll Number: 12345
Branch: ECE
College: NRI Institute of Technology
```

# Task 3: Addition of Two Numbers

## 1. Problem Statement

Write a Python program to read two numbers and display their sum.

## 2. Algorithm

1. Start
2. Read the first number
3. Read the second number
4. Add the two numbers
5. Display the sum
6. Stop

## 3. Flowchart

Start → Input First Number → Input Second Number → Add Numbers → Display Sum → Stop

## 4. Python Source Code

```python
a = float(input("Enter first number: "))
b = float(input("Enter second number: "))

sum = a + b

print("Sum =", sum)
```

## 5. Sample Input/Output

Input:
10
20

Output:
Sum = 30.0


# Task 4: Area of Circle Calculation
 
## 1. Problem Statement

 Write a Python program to calculate the area of a circle for a given radius.

## 2. Algorithm
Start
Read the radius of the circle
Calculate the area using the formula: Area = π × r × r
Display the area
Stop
## 3. Flowchart

Start → Input Radius → Calculate Area = 3.14 × r × r → Display Area → Stop

## 4. Python Source Code
```python
radius = float(input("Enter the radius: "))

area = 3.14 * radius * radius

print("Area of Circle =", area)
```
## 5. Sample Input/Output

Input:
5

Output:
Area of Circle = 78.5


# Task 5: Area of Rectangle Calculation
## 1. Problem Statement

Write a Python program to calculate the area of a rectangle using length and breadth.

## 2. Algorithm
Start
Read the length of the rectangle
Read the breadth of the rectangle
Calculate the area using the formula: Area = Length × Breadth
Display the area
Stop
## 3. Flowchart

Start → Input Length and Breadth → Calculate Area = Length × Breadth → Display Area → Stop

## 4. Python Source Code
```python
length = float(input("Enter the length: "))
breadth = float(input("Enter the breadth: "))

area = length * breadth

print("Area of Rectangle =", area)
```
## 5. Sample Input/Output

Input:
10
5

Output:
Area of Rectangle = 50.0


# Task 6: Temperature Conversion
1. Problem Statement

Write a Python program to convert temperature from Celsius to Fahrenheit.

## 2. Algorithm
Start
Read the temperature in Celsius
Convert Celsius to Fahrenheit using the formula: Fahrenheit = (Celsius × 9/5) + 32
Display the Fahrenheit temperature
Stop
## 3. Flowchart

Start → Input Celsius Temperature → Calculate Fahrenheit = (C × 9/5) + 32 → Display Fahrenheit → Stop

## 4. Python Source Code
```python
celsius = float(input("Enter temperature in Celsius: "))

fahrenheit = (celsius * 9/5) + 32

print("Temperature in Fahrenheit =", fahrenheit)
```
## 5. Sample Input/Output

Input:
25

Output:
Temperature in Fahrenheit = 77.0

# Task 7: Unit Conversion Program
## 1. Problem Statement

Write a Python program to convert kilometers to meters, meters to centimeters, and kilograms to grams.

## 2. Algorithm
Start
Read distance in kilometers
Convert kilometers to meters
Convert meters to centimeters
Read weight in kilograms
Convert kilograms to grams
Display all converted values
Stop
## 3. Flowchart

Start → Input Kilometers → Convert to Meters → Convert to Centimeters → Input Kilograms → Convert to Grams → Display Results → Stop

## 4. Python Source Code
```python
kilometers = float(input("Enter distance in kilometers: "))
kilograms = float(input("Enter weight in kilograms: "))

meters = kilometers * 1000
centimeters = meters * 100
grams = kilograms * 1000

print("Meters =", meters)
print("Centimeters =", centimeters)
print("Grams =", grams)
```
## 5. Sample Input/Output
Input:
5
2

Output:
Meters = 5000.0
Centimeters = 500000.0
Grams = 2000.0

# Task 8: Swap Two Variables
## 1. Problem Statement

Write a Python program to interchange the values of two variables and display the result.

## 2. Algorithm
Start
Read two variables
Store the first variable in a temporary variable
Assign the second variable to the first variable
Assign the temporary variable to the second variable
Display the swapped values
Stop
## 3. Flowchart

Start → Input A, B → Swap Values → Display Swapped Values → Stop

## 4. Python Source Code
```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

temp = a
a = b
b = temp

print("After Swapping:")
print("a =", a)
print("b =", b)
```
## 5. Sample Input/Output

Input:
10
20

Output:
After Swapping:
a = 20
b = 10

# Task 9: Student Marks Calculator
## 1. Problem Statement

Write a Python program to calculate the total marks obtained by a student in five subjects.

## 2. Algorithm
Start
Read marks of five subjects
Calculate the total marks
Display the total marks
Stop
## 3. Flowchart

Start → Input Marks of 5 Subjects → Calculate Total Marks → Display Total Marks → Stop

## 4. Python Source Code
```python
sub1 = float(input("Enter marks of Subject 1: "))
sub2 = float(input("Enter marks of Subject 2: "))
sub3 = float(input("Enter marks of Subject 3: "))
sub4 = float(input("Enter marks of Subject 4: "))
sub5 = float(input("Enter marks of Subject 5: "))

total = sub1 + sub2 + sub3 + sub4 + sub5

print("Total Marks =", total)
```
## 5. Sample Input/Output

Input:
80
75
90
85
70

Output:
Total Marks = 400.0

# Task 10: Percentage Calculator
## 1. Problem Statement

Write a Python program to calculate the percentage of marks obtained in an examination.

## 2. Algorithm
Start
Read marks obtained in five subjects
Calculate the total marks
Calculate the percentage using the formula:
Percentage = (Total Marks / Maximum Marks) × 100
Display the percentage
Stop
## 3. Flowchart

Start → Input Marks of 5 Subjects → Calculate Total Marks → Calculate Percentage → Display Percentage → Stop

## 4. Python Source Code
```python
sub1 = float(input("Enter marks of Subject 1: "))
sub2 = float(input("Enter marks of Subject 2: "))
sub3 = float(input("Enter marks of Subject 3: "))
sub4 = float(input("Enter marks of Subject 4: "))
sub5 = float(input("Enter marks of Subject 5: "))

total = sub1 + sub2 + sub3 + sub4 + sub5
percentage = (total / 500) * 100

print("Percentage =", percentage, "%")
```
## 5. Sample Input/Output

Input:
80
75
90
85
70

Output:
Percentage = 80.0 %
