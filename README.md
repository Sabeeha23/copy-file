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
Add text into the file.
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output.
## PROGRAM:
```
#Developed by: Sabeeha Shaik
#Register Number: 23012003

with open("text.txt","r") as f1:
  with open("copy.txt",'w') as f2:
      line = f1.read()
      f2.write(line)
```
### OUTPUT:
![Screenshot 2023-12-29 223330](https://github.com/Sabeeha23/copy-file/assets/150231876/d3d02ba8-5cf0-42a8-ac71-af335abb48b8)
![image](https://github.com/Sabeeha23/copy-file/assets/150231876/996a4326-3be1-4376-8903-fa929e0def3b)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
