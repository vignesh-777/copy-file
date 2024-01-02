# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name and location from the user.

### Step 2:
Give a new file name to create a copy of a file content.

### Step 3:
Read the file and close the file.

### Step 4:
Now write the content in the new file.

### Step 5:
When done print"File copied successfully".

### Step 6:
End of the program
## PROGRAM:
```py
#To write a program for copying the contents from one file to another file.
#Developed by: vignesh R
#RegisterNumber: 23005542
with open("file1.txt","r") as fp: 
    x = fp.read()
with open("copyfile.txt","w") as fp1: 
    fp1.write(x)
```
### OUTPUT:
![](./program.png)
### old file
![](./old%20file.png)
### created file
![](./new%20file.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.