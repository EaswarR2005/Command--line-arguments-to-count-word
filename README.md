# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Import the sys module.

### Step 2: 

Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

### Step 3: 

Read the file using read() method

### Step 4: 

Use split() method to split the file content into words.

### Step 5: 

Use len() to find the total words.

### Step 6: 

Run the program to determine the number of words in the file created.

## PROGRAM:
```
python program for getting the word count from the contents of a file using command line arguments.
Develpoed By: EASWAR R
RegisterNumber:212223230053

import sys
fp=open(sys.argv[1])
wordcount=0
for i in fp:
    words=i.split()
    wordcount+=len(words)
print("Total no of words in file",wordcount)
fp.close()
```

### OUTPUT:
## PROGRAM OUTPUT:
![image](https://github.com/EaswarR2005/Command--line-arguments-to-count-word/assets/146931525/ada85194-3ec5-4a23-baf4-9611e758f0e2)

## text2.txt:
![image](https://github.com/EaswarR2005/Command--line-arguments-to-count-word/assets/146931525/4a927dbb-404e-4f19-b30a-cf1226adddbb)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
