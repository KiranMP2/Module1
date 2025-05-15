# Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```
a=int(input())

if(a%2==0):
     print("EVEN")
else:
     print("ODD")
```
## Output
![Screenshot 2025-04-28 190627](https://github.com/user-attachments/assets/cceb1445-f4ad-4762-b1dd-fd8b35d515ff)
## Result
Thus,the python program was executed successfully


# Ex 1:Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
```
a = (False == True)
b = (False== 0)
c = False + True
d = False + 5

print("a is",a)
print("b is",b)
print("c:",c)
print("d:",d)
```

## Output
![Screenshot 2025-04-28 190645](https://github.com/user-attachments/assets/a141ee30-9f06-4703-ba13-a41838380691)
## Result
Thus, the python program was executed successfully

# Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```
v = 'T'
w = "a"
print(v)
print(w)
```
## Output
![Screenshot 2025-04-28 190703](https://github.com/user-attachments/assets/71e9266f-f97e-4d48-ba84-c7fbffc69e6b)
## Result
Thus, the python program was executed successfully

# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
```
real_part = float(input())
imaginary_part = float(input())
complex_number = complex(real_part, imaginary_part)

print(complex_number)
print(complex_number.real)
```
## Output
![Screenshot 2025-04-28 190718](https://github.com/user-attachments/assets/54a48a7f-2648-4e4e-855f-0044b5fc793d)
## Result
Thus,the python program was executed successfully

# Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```
men_stepped_on_the_moon=int(input())
print(men_stepped_on_the_moon)
```
## Output
![Screenshot 2025-04-28 190730](https://github.com/user-attachments/assets/fadb8920-9da4-4af5-84b0-93e7f47f67c9)
## Result
Thus,the python program was executed successfully
