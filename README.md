# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
start the program

### Step 2: 
import the file
 
### Step 3: 
open the file

### Step 4: 
write the function to count the count

### Step 5: 
print the result

### Step 6:
end the program

## PROGRAM:
```
#This program developed by: Yuvaraj v
#number:23013769

import sys
f1=open(sys.argv[0])
data=f1.read()
word=data.split()
print("The word count is",len(word))
f1.close
```

### OUTPUT:
![Screenshot 2023-12-24 163309](https://github.com/YuvarajVB/command-line-arguments-to-count-word/assets/151488375/bba4fd93-25a6-4d3a-a7f3-64e5ac2956dc)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
