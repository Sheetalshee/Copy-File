# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file form which we need to copy the text.

Again using the with keyword to open the empty file.

### Step 2:
Using keyword "with" to open the requied file.

### Step 3:
Again using the with keyword to open the empty file.

### Step 4:
The empty file is open by using 'W' which is used to write only.

### Step 5:
The four function is used to take each line from the main file.

## PROGRAM:
```
with open ("text.txt") as fp:
  with open("file.txt","w") as fp1:
    line= fp.read()
    fp1.write(line)
```
### OUTPUT:
![243200118-c30522e5-1f21-48eb-a61a-9bb220640fcf](https://github.com/Sheetalshee/Copy-File/assets/144979107/b4ad647f-5589-4331-a3f8-c6fb00ea3e9e)
![243200120-e9e52571-d23d-40f6-8855-605ca26aeb8b](https://github.com/Sheetalshee/Copy-File/assets/144979107/349aa118-895e-4dc1-94bb-2b15ad
![243200124-f87ecf70-bf60-4f08-966b-a14d2708e9ed](https://github.com/Sheetalshee/Copy-File/assets/144979107/44cee774-2d81-44f5-887b-9d331ac33d3c)
49ddde)

## RESULT:
Thus the program is written to copy the contents from one file to another file executed successfully.
