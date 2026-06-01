# 1. Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
<img width="186" height="114" alt="Screenshot 2026-06-01 101554" src="https://github.com/user-attachments/assets/1d52cb2f-c037-4cd6-aa52-861091e198a4" />


## Output
<img width="382" height="137" alt="Screenshot 2026-06-01 101607" src="https://github.com/user-attachments/assets/3b376e46-e699-4aad-9b63-080dafb4207b" />

## Result
The execution of the code was successfully done


# 2. Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
<img width="341" height="156" alt="Screenshot 2026-06-01 102100" src="https://github.com/user-attachments/assets/a6fcb214-8724-40ea-9158-5a3a11475aae" />


## Output
<img width="183" height="127" alt="Screenshot 2026-06-01 102113" src="https://github.com/user-attachments/assets/67d940cc-c97e-492d-b7f2-39088ce92199" />


## Result
The execution of the code was successfully done.

# 3. Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
<img width="266" height="120" alt="Screenshot 2026-06-01 102524" src="https://github.com/user-attachments/assets/f68ea751-2caf-4ad1-b82a-b38aba7d7f2a" />


## Output
<img width="359" height="193" alt="Screenshot 2026-06-01 102536" src="https://github.com/user-attachments/assets/809145b8-42d9-4729-8cf8-3ebb5fb67c79" />

## Result
The execution of the code was successfully done.

# 4. Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.


## 🧠 Algorithm

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


## 🧪 Program
<img width="656" height="271" alt="Screenshot 2026-06-01 103225" src="https://github.com/user-attachments/assets/022833f7-d542-4282-aa06-850df9c9f7e5" />


## Sample Output
<img width="360" height="253" alt="Screenshot 2026-06-01 103305" src="https://github.com/user-attachments/assets/d3a480d7-317d-4099-b8be-5e5dcab62564" />


## Result
The execution of the program was successfully done.

# 5. Loops in Python: Palindrome Number Checker

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
