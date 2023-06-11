# command-line-arguments-to-count-word

## AIM:

To write a python program for getting the word count from the contents of a file using command line arguments.

## EQUIPEMENT'S REQUIRED: 

PC
Anaconda - Python 3.7

## ALGORITHM: 

Step 1: Import sys module.

Step 2: Open the file with sys.argv[1].

Step 3: Use the for loop to select the content in file.

Step 4: Use split function to to separate the file content into words or strings.

Step 5: Count the length of the words using len.

Step 6: Print the number of words.

## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments.
Programmed by: SANJAY T
Ref.No.: 212222110039

import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```
### OUTPUT:

![244742938-a41544e5-3004-4ae3-be96-c8b2e9810798](https://github.com/sanjaythiyagarajan/command-line-arguments-to-count-word/assets/119409242/8bb08ae9-0d31-4819-88fa-8ff48c51cdde)

![244743301-3988feeb-892a-4e5e-a948-b2df5b2e828d](https://github.com/sanjaythiyagarajan/command-line-arguments-to-count-word/assets/119409242/647e79d7-ff02-44bb-9364-65dec989716d)

![244743250-588db9f1-08e0-40f5-9a3c-6c058364d78e](https://github.com/sanjaythiyagarajan/command-line-arguments-to-count-word/assets/119409242/212d54aa-9e85-499c-b434-f89ade0609a8)




## RESULT:

Thus the program is written to find the word count from the contents of a file using command line arguments.
