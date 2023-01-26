# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Import the sys module.

### Step 2: 

Pass the filename as the first argument after the name of script.Open the file as sys.argv[1]
 
### Step 3: 

Read the file using read() method.

### Step 4:  

Use split() method to split the file content into words.

### Step 5: 

Use len() to find the total words.

### Step 6: 

Run the program to determine the number of words in the file created.

## PROGRAM:
```python
Program to sort the elements in the list using the Selection Sort algorithm.
Developed by: s.thirisha
RegisterNumber: 22001920
import sys
count = 0
with open(sys.argv[1],'r')as f1:
    for line in f1:
        word = line.split()
        count += len(word)
print("word count in file = ",count)
```

### OUTPUT:
![Screenshot_20230126_110210](https://user-images.githubusercontent.com/120380280/214765522-3f104e93-76ed-47fb-b51c-2d82767f62dc.png)
![Screenshot_20230126_110235](https://user-images.githubusercontent.com/120380280/214765552-86230dd0-3eee-4c80-911d-106550dfee86.png)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
