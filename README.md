# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
As a first step import sys
### Step 2: 
 Create a file.txt and add a content
### Step 3: 
Split the words using .split() function
### Step 4:  
Read the words
### Step 5: 
Run the program
### Step 6: 
Run the program
## PROGRAM:
#Developed by:  Vijayaraj.V
#Register Number: 22001903

import sys
fp= open(sys.argv[1])
data=fp.read()
words=data.split()
print("Number of words:",len(words))

### OUTPUT:

![new1](https://user-images.githubusercontent.com/121303741/215317584-049caef7-e6e8-4ec1-873f-e9f2d215dddf.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
