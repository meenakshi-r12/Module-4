# Ex-4A DICTIONARY
##  Aim
To write a python program that asks the user to enter an integer n and return a dictionary whose keys are integers 1, 2, 3, ... n and whose values are 1! , 2! , 3! , … , n!.
## ALGORITHM:
1.	Define a function named "factorial" that takes a parameter "n" and returns the factorial of "n".
2.	Read input and convert it to an integer, storing it in variable "n".
3.	Initialize an empty dictionary "dic1".
4.	Start a loop to iterate from 1 to "n-1":
a. Calculate the factorial of the current number using the "factorial" function and store it in the dictionary "dic1" with the current number as the key.
5.	Print the obtained dictionary "dic1" using a formatted string.
6.	End of the program.
## PROGRAM:
```
def factorial(n): fact = 1
for i in range(1,n+1): fact*=i
return fact n = int(input()) dic1 = {}
for i in range(1,n):
   dic1[i]=factorial(i)
print(f"The obtained dictionary is d = {dic1}")
```
## Output
![Screenshot (74)](https://github.com/user-attachments/assets/b87385ab-82b3-4c41-ac73-88574b2e75d9)

## Result
Thus, the required program is written and executed successfully.
