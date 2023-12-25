# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC 
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:From shutil import copy file

### Step 2: From sys import exit
 
### Step 3: Getting input for source file

### Step 4:  Getting input for target file

### Step 5: Giving condition for files

### Step 6: Getting statement from the user to print or not want to print

## PROGRAM:
```
'''
#Programe to copy the file.
#Developed by:DHARSANKUMAR R 
#Registernumber:21223240028
'''
print("Enter the name of source file:")
sFile=input()
print("Enter the name of target files:")
tFile=input()
fileHandle=open(sFile,"r")
texts=fileHandle.readlines()
fileHandle.close()
fileHandl=open(tFile,"w")
for s in texts:
    fileHandle.write(s)
fileHandle.close()
print("\nFile Copied Successfully!")
```

### OUTPUT:
![image](https://github.com/DHARSAN23014208/copy-file/assets/149365413/31e1c387-0dfb-49f1-a947-4f28d90c12a6)
![image](https://github.com/DHARSAN23014208/copy-file/assets/149365413/fb4da7c5-6bfd-45e7-b695-c6874e22feee)
![image](https://github.com/DHARSAN23014208/copy-file/assets/149365413/3972870f-d2a7-43e7-bb5e-2d41e91788a1)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
