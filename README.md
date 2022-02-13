# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
From shutil import copyfile
Step 2:
Take users the name of source and destination files.
Step 3:
if the source there is a source file then copy the contents of source file to the destination
file.
Step 4:
Read each line from the input file and write it into the output file.
Step 5:
Then print.
Step 6:
End the program.

## PROGRAM:
```
with open("record.txt","r")as fp:
    with open("file1.txt","w")as fp1:
        line=fp.read()
        fp1.write(line)
```

### OUTPUT:
![output1](./fileoutput.png)
![output2](./recordoutput.png)



## RESULT:
Thus the program is written to copy the contents from one file to another file.