# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.
### Step 2: 
 Read the file and store in a variable.
### Step 3: 
Now create a new file in which we want to paste the content using write access mode.
### Step 4:  
Use write function to copy the read file that has been stored in the variable.
### Step 5: 
The content in the original file will be copied in the new file.
### Step 6: 
End the program.
## PROGRAM:
```
#python program for copying a file
#developed by: MANOJ G
#registration number:212222240060
with open("sample1.txt", "r") as firstfile:
    with open("sample2.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)  
```
### OUTPUT:

![243254800-6ad570fa-192f-45a3-986b-3297096eb19b](https://github.com/Danielmanoj/copy-file/assets/69635071/79bdee62-3ad4-4c1b-9891-016e7cc6e037)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
