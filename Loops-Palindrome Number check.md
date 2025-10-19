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
num=int(input())
temp=num
rev=0
while temp>0:
   rev=(10*rev)+temp%10
   temp//=10
if num==rev:
   print("The given number is palindrome")
else:
   print("The given number is not a palindrime")
```
## Output
<img width="1540" height="130" alt="image" src="https://github.com/user-attachments/assets/c7fe1d5e-88c8-4cd4-b38a-73bed4290e37" />
<img width="1531" height="167" alt="image" src="https://github.com/user-attachments/assets/b3d921dc-ce27-44ba-9db6-2304b045d6a9" />


## Result
Thus,To write a Python program that checks whether a given number is a **palindrome** using loops.
