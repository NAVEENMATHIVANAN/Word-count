# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Assign value for num_word
### Step 2: 
 Open the file in read mode.
### Step 3: 
Iterate using for loop.
### Step 4:  
Increment the word with length of the word.
### Step 5: 
Print the number of words in text.

## PROGRAM:
```
'''
Program to count the words in a file
Devoloped by: NAVEEN KUMAR M
Register Number: 212222110028
'''
fname=input("Enter thr file name: ")
num_words = 0

with open(fname,'r') as f:
  for line in f:
    words = line.split()
    num_words+=len(words)
print('Number of words: ',num_words)
```
### OUTPUT:
![image](https://github.com/NAVEENMATHIVANAN/Word-count/assets/119394582/1f91887c-c636-41df-90fe-c0dee6124e7b)



## RESULT:
Thus the program is written to find the word count from a text.
