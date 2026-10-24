FACTORIAL USING RECURSION IN PYTHON

1. Aim:
   To write a Python program to calculate the factorial of a number using recursion.

2. Description:
   The factorial of a non-negative integer is the product of all positive integers up to that number. The factorial of 0 and 1 is 1.

3. Requirements:

* Python 3
* Any Python IDE or editor

4. Program:
   def factorial_recursive(n):
   if n < 0:
   return "Factorial is not defined for negative numbers."

   if n == 0 or n == 1:
   return 1

   return n * factorial_recursive(n - 1)

num = 6
print(f"The factorial of {num} is {factorial_recursive(num)}")

5. Sample Output:
   The factorial of 6 is 720

6. Explanation:

* If n is negative, the function returns an error message.
* If n is 0 or 1, the function returns 1.
* Otherwise, the function calls itself with n - 1 and multiplies the result by n.

7. Conclusion:
   The program successfully calculates the factorial of a number using recursion.
