# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

### Step 1:
open the first line using with open('fi.txt','a') as firstfile

### Step 2:
open the second file using with open('f2.txt,'a') as secondfile
 
### Step 3: 
use for the loop to write in secondline

### Step 4:
write in the secondline using secondfile.write(line)  

### Step 5: 
print the output

### Step 6:
end the program 

## PROGRAM:
Developed by: Soundariyan M N

Register no : 22008347

```python
with open('f1.txt','r') as firstfile:
    with open('f2.txt','a') as secondfile:
        secondfile.write(line)
```        

### OUTPUT:
![model](out.png)
![model](put.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.