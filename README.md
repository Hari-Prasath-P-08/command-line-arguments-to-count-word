# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:
### Step 1:
Import sys module
### Step 2:
Using sys module,open a file with read mode
### Step 3:
Read the file and split the file and store it in the variable
### Step 4:
Print the length of the variable
### Step 5:
End the program

## PROGRAM:
```
# To write a program to count the contents of the file using command line arguments.
# Developed by: Hari Prasath. P
# Reference number: 23005079
f = open('/content/drive/MyDrive/Colab Notebooks/Summa.txt','r')

import sys
n = open(sys.argv[0],'r')
a = f.read().split()
print(len(a))
```
### OUTPUT:
![output](/Screenshot%202023-07-30%20155738.png)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
