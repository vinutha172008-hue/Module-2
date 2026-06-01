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
<img width="401" height="293" alt="Screenshot 2026-06-01 104618" src="https://github.com/user-attachments/assets/4175ec7a-63f7-4523-b70c-ca451ea392f2" />


## Output
<img width="386" height="169" alt="Screenshot 2026-06-01 104627" src="https://github.com/user-attachments/assets/59f3b07c-7043-4461-9280-90bd4c761ea5" />


## Result
The execution of the code was successfully done.
