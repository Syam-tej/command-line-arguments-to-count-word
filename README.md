# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
# Step 1: Create a text file in a specific loaction of interest.
# Step 2: On the same location as the text file, create a python program file.
# Step 3: In python Program, import sys and open a text file with argument "sys.argv[1]"
# Step 4: using read() and split(), split the lines in the file into a sequence of words.
# Step 5:using len() count the number of words in the text file.
# Step 6: In command prompt, initiate python followed by program name and text file name to get the output.

## PROGRAM:
```
python program for getting the word count from the contents of a file using command line arguments.
Develpoed By:SYAM TEJ
RegisterNumber:21002938
```
# in python file "program.py"
```
import sys
f1=open(sys.argv[1])
data=f1.read()
word=data.split()
print("The word count is",len(word))
f1.close()
```
### OUTPUT:
Text File "File1.txt":
![image](https://user-images.githubusercontent.com/94165326/153735949-b6ccc239-3e9a-418a-9e35-08278d7fd1f9.png)


Command Powershell prompt:
![image](https://user-images.githubusercontent.com/94165326/153735965-b5b3e572-539f-4ba9-95c6-cd9de0914690.png)





## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
