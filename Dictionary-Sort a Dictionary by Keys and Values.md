## Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:

Alphabetically by keys
Alphabetically by values

## Aim
To write a Python program that sorts a dictionary's:

Keys in alphabetical order
Values in alphabetical order
## Algorithm
Start the program.
Define a dictionary with key-value pairs.
Sort by Keys:
Use sorted(dictionary.items())
Convert the result to a dictionary using dict()
Sort by Values:
Use sorted(dictionary.items(), key=lambda item: item[1])
Convert the result to a dictionary using dict()
Display the original and sorted dictionaries.
End the program.
## Program
```
def dictionairy(): 
# Declaring hash function      
key_value ={}    
# Initializing the value 
key_value[2] = 56       
key_value[1] = 2 
key_value[5] = 12 
key_value[4] = 24 
key_value[6] = 18      
key_value[3] = 323 
print ("Keys and Values sorted", 
"in alphabetical order by the value") 
# Note that it will sort in lexicographical order 
# For mathematical way, change it to float 
print(sorted(key_value.items(), key = 
lambda kv:(kv[1], kv[0])))
```
## Output

![Screenshot (85)](https://github.com/user-attachments/assets/16417fea-1c76-45a8-944c-39d98951acb0)

## Result
Thus,the program has been executed successfully.


