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

def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python

def max_marks(marks):
    large = max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python

def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```



## Output:
![Screenshot 2024-03-24 184242](https://github.com/Samakas/FindMaximum/assets/154731670/99e71500-ecbf-4466-b462-de719f2e5ead)
![Screenshot 2024-03-24 184252](https://github.com/Samakas/FindMaximum/assets/154731670/5b3ff891-0690-4b95-82a6-1adfce0fb1df)
![Screenshot 2024-03-24 184305](https://github.com/Samakas/FindMaximum/assets/154731670/ed2137bd-b2fa-4e9a-a6a8-77766f5a7866)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
