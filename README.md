# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define the function as copy with arguements as existing file name and new file name.

### Step 2: 
Open the existing file to read.
 
### Step 3: 
Open the new file to write.

### Step 4:  
Copy the contents from existing file to new file.


### Step 5: 
Get the inputs from the user for existing file and new file. Call the function.

### Step 6: 
End the program.

## PROGRAM:
### Program to find the word count using command line arguments
### Developed by: ARUNMOZHI VARMAN T
### Register Number: 212223230022
```
def copy(fname,newfile):
  with open(fname,'r')as fp:
    with open(newfile,'w')as fp1:
      data1=fp.read()
      fp1.write(data1)
fname=input("Enter an existing file: ")
newfile=input("Enter a name for new file: ")
copy(fname,newfile)
```
### OUTPUT:
![image](https://github.com/ArunmozhiVarmanT/copy-file/assets/144870523/ad63e77e-45ef-4334-895e-bd69e86290ce)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
