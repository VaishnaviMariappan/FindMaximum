# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step 1:
 Get the list of marks as input
### Step 2:	
 Use the sort() function or max() function or use the for loop to find the maximum mark.
### Step 3:
 Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```
Program to mark the maximum of marks using the list method sort
Developed by: Vaishnavi M
RegisterNumber: 21500310

def max_marks(marks):
    #Write your code here
    marks.sort()
    maxi=marks[-1]
    return maxi

```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: Vaishnavi M
RegisterNumber: 21500310

def max_marks(list1):
    max_mark=0
    for i in list1:
        if i>max_mark:
            max_mark=i
    return max_mark
    
```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: Vaishnavi M
RegisterNumber: 21500310

def max_marks(marks):
    x=max(marks)
    return x

```
## Sample Input and Output
![output](./output1.png) 
![output](./output2.png)
![output](./output3.png)
## Output:

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.