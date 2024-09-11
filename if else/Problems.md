 Variables
1.	Swapping Values: Write a program that swaps the values of two variables a and b if they are different. Use an if statement to check if the values are different before swapping.
Test Case:
o	Input: a = 5, b = 10
o	Output: a = 10, b = 5
o	Input: a = 7, b = 7
o	Output: a = 7, b = 7
Code:
```
a = int(input("Enter value for a: "))
b = int(input("Enter value for b: "))

if a == b:
    print("a =", a)
    print("b =", b)
else:
    temp = a
    a = b
    b = temp
    print("Swapped values")
    print("a =", a)
    print("b =", b)
```
```
a=int(input("Enter number  A = "))
b=int(input("Enter number  B = "))
if a!=b:
    temp=a
    a=b
    b=temp
    print("A = ",a),print("B = ",b)
else:
    print("A = ",a),print("B = ",b
```
2.	Grade Assignment: Create a program that assigns a letter grade based on a numeric score using if and else. The grades are as follows: "A" for 90 and above, "B" for 80-89, "C" for 70-79, "D" for 60-69, and "F" for below 60.
Test Case:
o	Input: score = 85
o	Output: Grade = B
o	Input: score = 45
o	Output: Grade = F
Code
```
n = int(input())

if n >= 90:
    print("A")
elif 80 <= n < 90:
    print("B")
elif 70 <= n < 80:
    print("C")
elif 60 <= n < 70:
    print("D")
else:
    print("F")
```
3.	Sign Check: Implement a function that checks if a variable x is positive, negative, or zero and prints the appropriate message.
Test Case:
o	Input: x = 10
o	Output: Positive
o	Input: x = -3
o	Output: Negative
o	Input: x = 0
o	Output: Zero
Code 
```
a = int(input())
if a > 0:
    print("pos")
elif a < 0:
    print("Neg")
elif a == 0:
    print("Zero")
else:
    print("Appropriate mess")
```
4.	Age Check: Write a program that uses a variable to store a user’s age and prints "Minor" if the age is under 18, otherwise prints "Adult."
Test Case:
o	Input: age = 16
o	Output: Minor
o	Input: age = 21
o	Output: Adult
Code
```
a = int(input())
if a < 18:
    print("minor")
elif a >= 18:
    print("Major")
```
