# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import numpy as num
### Step 2: 
Enter input values
### Step 3: 
Write python program for getting the word count from the contents of a file using
command line arguments
### Step 4:  
Run the program
### Step 5: 
Input the values
### Step 6: 
End the program
## PROGRAM:
program to find the number of words in a text file
Developed by : THARUN SRIDHAR 
Register number : 212223230230
num=0
with open("story.txt","r") as f1:
for i in f1:
word=i.split()
num += len(word)
print("The number of words are in the file is ",num)
![image](https://github.com/Tharun0707/Word-Count/assets/145548496/8991d7ad-fa02-45be-9cca-13c4ea18741c)



### OUTPUT:
![image](https://github.com/Tharun0707/Word-Count/assets/145548496/2cc90954-7925-4a81-b648-749db05b3f98)




## RESULT:
Thus the program is written to find the word count from a text.
