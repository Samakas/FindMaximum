# Find the maximum of a list of numbers
## Date: 23/03/2024
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
Developed By: Samakash.R.S
Register Number:212223230182

def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python
Developed By: Samakash.R.S
Register Number:212223230182

def max_marks(marks):
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
Developed By: Samakash.R.S
Register Number:212223230182

def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```



## Output:
![alt text](<Screenshot 2024-04-06 110704.png>)
![alt text](<Screenshot 2024-04-06 110725.png>)
![alt text](<Screenshot 2024-04-06 110738.png>)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
