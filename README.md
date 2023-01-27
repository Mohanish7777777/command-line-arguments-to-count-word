# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys from the package.

### Step 2:
Start the value from 0 to count.

### Step 3:
Use with open() to open the file.

### Step 4:
Start the for loop to count the number of words.

### Step 5:
Print the required statements.

### Step 6:
End the program.
## PROGRAM:
```python
# Reference No: 22002294
# Developed By: Mohanish.K
import sys
count=0
with open(sys.argv[1],'r') as f:
        for line in f:
            word=line.split()
            count+=len(word)
print("Word Count in File=",count)   
```
### OUTPUT:
![image](https://user-images.githubusercontent.com/111619160/215005842-85e74a44-6323-4169-a385-c1147249a93f.png)
#Termial side
![image](https://user-images.githubusercontent.com/111619160/215005974-a6a4eb60-23ea-455a-8f77-4c29ce3e452c.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
