# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Import sys module to use command line arguments.

Step 2:
Create a file pointer and open the file which is passed in command line.

Step 3:
Initialize word count as zero.

Step 4:
For each line in file, split it into words and find number of the words in every line.

Step 5:
Sum the number of words in each line.

Step 6:
Display the total words in the file.

## PROGRAM:
```
Developed by: Mohanram Gunasekar
Register no: 212223240095
import sys
fp=open(sys.argv[1])
wordcount=0
for i in fp:
    words=i.split()
    wordcount+=len(words)
print("Total no of words in file is",wordcount)
fp.close()
```
### OUTPUT:
![331276462-c4f50fa7-dc3c-43c3-bf33-2afc0f73d768](https://github.com/MohanramGunasekar/Command--line-arguments-to-count-word/assets/139841812/b70f2a39-5612-43a8-88c2-29c7781f4346)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
