## Ex-4B EXCEPTIONS
## AIM:
To write a python program for solving key error using exception handling & to find whether key is exist or not.
## ALGORITHM:
1.	Define a dictionary "dic1" with key-value pairs.
2.	Start a try-except block:
a.	Inside the try block:
i.	Try to access the values associated with keys 1, 2, and 4 in the dictionary "dic1" and print them.
b.	If an exception is raised (key does not exist), execute the code inside the except block:
i.	Print "The key does not exist!".
3.	End of the program.
## PROGRAM:
```
dic1 = {1:'Hello',2:'World', 3:'Python'} try:
print(dic1[1]) print(dic1[2]) print(dic1[4])
except:
print("The key does not exist!")
```
## OUTPUT
![image](https://github.com/user-attachments/assets/51d692f5-94b1-415d-b478-50bb0fd49ad8)

## RESULT:
Thus, the required program is written and executed successfully.
 
