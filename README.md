# EX 2 (A) Built-in Functions -Binary Conversion Using Built-in Functions in Python

## Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## Program
```
x=16
y=bin(x)
print(y)
```

## Output
<img width="326" height="277" alt="image" src="https://github.com/user-attachments/assets/e34ac3a4-31a3-4f00-bb25-45801e243932" />

## Result
Thus,the Python program to convert the number 16 into its binary representation using built-in Python functions is created successfully.


# EX 2 (B) Functions in Python: Modulo Calculator

## Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## Program
```
def result(a, b):
    modulo_value = a % b
    return modulo_value

a=int(input())
b=int(input())
print("modulo is", result(a, b))
```

## Output
<img width="567" height="317" alt="image" src="https://github.com/user-attachments/assets/4443e511-c188-4440-8ec9-faebbbe6e1d4" />

## Result
Thus, the Python program that defines a function which accepts two values and returns their modulo using the % operator is created successfully.


# EX 2 (C) Lambda Function in Python: Addition of Two Numbers

## Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## Program
```
i=int(input())
j=int(input())
z=int(input())
f = lambda a, b,c: a+b+c
print(f(i, j,z))
```

## Output
<img width="535" height="415" alt="image" src="https://github.com/user-attachments/assets/a5e4aa77-2087-486f-be97-61b085a38af6" />

## Result
Thus, the program successfully defines a lambda function that computes the sum of two numbers and prints the result.


# EX 2 (D) Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## Program
```
rows = int(input())
coef = 1

for i in range(1, rows+1):
    for space in range(1, rows-i+1):
        print(" ",end="")
    for j in range(0, i):
        if j==0 or i==0:
            coef = 1
        else:
            coef = coef * (i - j)//j
        print(coef, end = " ")
    print()
```

## Output
<img width="544" height="618" alt="image" src="https://github.com/user-attachments/assets/a3f41201-1139-44c7-9ae1-2fcc3fe650a0" />

## Result
Thus,the Python program that generates Pascal's Triangle using numbers is created successfully.


## EX 2 (E) Loops in Python: Palindrome Number Checker

## Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## Program
```
num=int(input())
temp = num
count =0
while num>0:
    digit =num%10
    count= count*10+digit
    num//=10
if temp== count:
    print("The given number {} is a Palindrome".format(temp))
else:
    print("The given number {} is not a palindrome".format(temp))
```
## Output
<img width="1070" height="259" alt="image" src="https://github.com/user-attachments/assets/ebbdcded-2f3d-4161-93fd-2cee45836cfd" />

## Result
Thus, the python program to check whether the given number is palindrome or not is executed successfully.
