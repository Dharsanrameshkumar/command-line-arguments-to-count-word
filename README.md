# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
 
### Step 1:
Create a text file in a specific loaction of interest.

### Step 2:
On the same location as the text file, create a python program file.

### Step 3:
In python Program, import sys and open a text file with argument "sys.argv[1]"

### Step 4:
using read() and split(), split the lines in the file into a sequence of words.

### Step 5:
using len() count the number of words in the text file.

## PROGRAM:
```
#Program to find the Word Count using command line arguments
#Developed by: dharsan
#register Number:212223100003


fname=input("Enter the file name:")
num=0
with open(fname, 'r') as f:
    for i in f:
        words=i.split()
        num +=len(words)
print("The number of words are in the file is ",num)


```

### OUTPUT:
![Alt text](<Screenshot (96).png>)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
