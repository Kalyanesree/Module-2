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
