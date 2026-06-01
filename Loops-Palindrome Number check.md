## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
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

## 🧾 Program
```
num = int(input("Enter number to check if it is palindrome: "))

temp = num
rev = 0
while temp>0:
    rem = temp%10
    rev = rev*10+rem
    temp = temp//10

if rev==num:
    print(f"{num} is a palindrome")
else:
    print(f"{num} is not a palindrome")
```
## Output
<img width="507" height="74" alt="image" src="https://github.com/user-attachments/assets/4e484915-64b1-44f8-ac7f-ffdf51227f25" /><br>
<img width="494" height="70" alt="image" src="https://github.com/user-attachments/assets/1d21a71c-2c6c-43de-9532-8ac292dd8e61" />

## Result
Thus the program has been executed successfully
