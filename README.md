# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
Write some lines in that file. 
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output.
## PROGRAM:
Developed By: SHEETAL.R
Register No: 212223230206

def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)

### OUTPUT:
![Screenshot 2024-05-09 112455](https://github.com/Sheetalshee/Copy-File/assets/144979107/c4370c37-766f-4d8f-a3bd-7616c37339b0)
![Screenshot 2024-05-09 112527](https://github.com/Sheetalshee/Copy-File/assets/144979107/412e0868-b7c0-410c-b13c-ab40a6925750)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
