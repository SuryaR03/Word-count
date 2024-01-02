# Word-count
## AIM:
To write a python program for getting the word count from a text.
## ALGORITHM: 
### Step 1:
Start the program.
### Step 2: 
 Give the input string.
### Step 3: 
Print the original string.
### Step 4:  
using len(test_string.split()) get the result.
### Step 5: 
Print the word count.
### Step 6: 
End the program.
## PROGRAM:
```python
#python program for word count
#Developed by :Surya R
#Reference no : 23013019

def wordcount(filename):
count=0
with open(filename,"r") as f:
for data in f:
words=data.split()
for word in words:
count+=1
print("Total number of words:",count)
filename=input("Enter Filename:")
wordcount(filename)
```

### OUTPUT:
![WhatsApp Image 2023-12-29 at 23 56 01_c2e12a25](https://github.com/SuryaR03/Word-count/assets/147140237/0ae980ac-e154-492d-8f08-bf71061ce90e)
![WhatsApp Image 2023-12-29 at 23 56 58_845db703](https://github.com/SuryaR03/Word-count/assets/147140237/682086bf-d8d9-4d5a-b5e4-76f24c185ea4)



## RESULT:
Thus the program is written to find the word count from a text.
