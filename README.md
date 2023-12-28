# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
use open function to open the file in which we want to copy from and access it in read mode
### Step 2: 
 read the file and store it in a variable
### Step 3: 
now create a file in which we want topaste the content using write acces mode
### Step 4:  
use write function to copy the read file that has been stotred in the varible
### Step 5: 
the content in the original file will be copied in the new file
### Step 6: 
End the program
## PROGRAM:
```
# DEVELOPED BY : THILAKESHWARAN.K.P
# REFERANCE  NUMBER : 23013560

with open("Files.txt","r") as f1:
    with open("copy.txt","w") as f2:
        line = f1.read()
        f2.write(line)
```
### OUTPUT:
![PROG](https://github.com/Thilakeshwaran/copy-file/assets/147473132/2a88afdb-63c6-495b-867e-667228fb8e3f)

file.txt
![FILE](https://github.com/Thilakeshwaran/copy-file/assets/147473132/2779e25e-8a2d-4373-b4ea-57b99a66372b)

copy.txt
![COPY](https://github.com/Thilakeshwaran/copy-file/assets/147473132/7bce3ccb-d68c-457c-9f3e-baf08e58f03f)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
