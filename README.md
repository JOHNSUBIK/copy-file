# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
use open function to open the file in which we want to copy from and access it in read mode

Step 2:
read the file and store it in a variable

Step 3:
now create a file in which we want topaste the content using write acces mode

Step 4:
use write function to copy the read file that has been stotred in the varible

Step 5:
The content in the original file will be copied in the new file

Step 6:
End the program

## PROGRAM:

with open("Files.txt","r") as f1:
    with open("copy.txt","w") as f2:
        line = f1.read()
        f2.write(line)


### OUTPUT:

![image](https://github.com/JOHNSUBIK/copy-file/assets/150279319/c7894417-9556-42e0-9e2e-7a859980bc10)
![image](https://github.com/JOHNSUBIK/copy-file/assets/150279319/a45f5f33-8e26-4bac-a5e8-b404b85761fa)
![image](https://github.com/JOHNSUBIK/copy-file/assets/150279319/de519e73-cf56-4578-b514-0280f5101b20)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
