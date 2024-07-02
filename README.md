# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to know the number of words.
### Step 2: 
Use read access mode.
### Step 3: 
Use split() function inside the loop.
### Step 4:  
Iterate each and every value and increment it by 1.
### Step 5: 
Print outside the for loop.
### Step 6: 
End the program.
## PROGRAM:
```
'''
Program to count the words in the file.
Developed by: Senthil Kumar S
Register number: 212221230091
'''


with open("rumbling.txt","r") as fp:
    count=0
    for data in fp:
        a=data.split()
        for i in a:
            count+=1
    print("Total number of words:",count)
```
### FILE:
![rumbling](https://user-images.githubusercontent.com/93860256/153127465-05eabbb0-4456-455e-bf0b-9a89b178847b.PNG)


### OUTPUT:

![output](https://user-images.githubusercontent.com/93860256/153127510-7579021b-742a-448f-b5e7-cd6a86cd41d1.PNG)



## RESULT:
Thus the program is written to find the word count from a text
