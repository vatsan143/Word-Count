# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import numpy as np

### Step 2: 
 Enter the input values
### Step 3: 
Write python program for getting the word count from the contents of a file using command line arguments
### Step 4:  
Run the program
### Step 5: 
Input the values
### Step 6: 
End the program
## PROGRAM:
#program to find the number of words in a text file

#Developed by : G srivatsan 

#Register number : 212223230216

```
num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```

### OUTPUT:
![WhatsApp Image 2024-05-12 at 19 48 29](https://github.com/vatsan143/Word-Count/assets/147368204/3e213cb0-4af1-4f44-8b7e-b08c8652beba)

## RESULT:
Thus the program is written to find the word count from a text.
