# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program

```
def result(a,b):
    return a%b
    
x = 10
y = 3
print(x,"%",y,"=",result(x,y))
print()

a,b = map(int,input("Enter two numbers to perform Modulo operation: ").split())
print("Result of modulo operation:",result(a,b))
```
## Output
<img width="580" height="132" alt="image" src="https://github.com/user-attachments/assets/fdd1a53f-f2cc-404e-bc81-3ff894aeb937" />

## Result
Thus the program has been executed successfully.
