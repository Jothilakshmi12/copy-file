# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
 Write some lines in that sile.
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output.
## PROGRAM:
```
Developed by: Jothilakshmi
Register number: 212223110017
'''
def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an  Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)
```
### OUTPUT:
![copyoutput1](https://github.com/Jothilakshmi12/copy-file/assets/138849182/303542b2-e0e6-4060-bed6-2c00b9a86b3d)
![copyoutput2](https://github.com/Jothilakshmi12/copy-file/assets/138849182/2d5124a7-ca97-41bd-aeea-e804b73df588)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
