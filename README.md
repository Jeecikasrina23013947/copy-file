# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it
### Step 2: 
Open the text1.txt file in read mode
### Step 3: 
Create a copy.txt file using write mode
### Step 4:  
Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
```python
Program for copying the contents from one file to another file
Developed by: JEECIKASRINA M
Register Number: 23013947

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![293366207-98415898-13e3-4682-a2e0-8f7fe4e5cd23](https://github.com/Jeecikasrina23013947/copy-file/assets/148515300/7c13c5c7-6de3-4c71-a284-c923712c6ce0)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
