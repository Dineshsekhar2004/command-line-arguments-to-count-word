# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Import sys module

### Step 2:Open the file with sys.argv[1]
 
### Step 3:Use the for loop to select the content in file

### Step 4:Use split function to to separate the file content into words or strings

### Step 5:Count the length of the words using len

### Step 6:Print the number of words

## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: S.Dinesh
RegisterNumber: 21222230033

import sys
fp=open(sys.argv[1], 'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print("No of words in a file",count)
```

### OUTPUT:
![image](https://github.com/Dineshsekhar2004/command-line-arguments-to-count-word/assets/119405916/c856b646-9124-4ce6-ac40-f39c1a9a3e80)
![image](https://github.com/Dineshsekhar2004/command-line-arguments-to-count-word/assets/119405916/8738d8c0-0e2c-4b88-a84e-af9dd02e3f3d)
![image](https://github.com/Dineshsekhar2004/command-line-arguments-to-count-word/assets/119405916/0434dcf3-472b-44c7-abcb-a6592f0e9b49)




## RESULT:Thus the program is written to find the word count from the contents of a file using command line arguments.
Thus the program is written to find the word count from the contents of a file using command line arguments.
