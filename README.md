# Find the maximum of a list of numbers
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
```python 
''' 
Program to mark the maximum of marks using the list method sort
Developed by: Ganesh R
RegisterNumber: 212222240029
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return larg
```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Ganesh R
RegisterNumber: 212222240029
'''
def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Ganesh R
RegisterNumber: 212222240029
'''
def max_marks(list1):
    maximum=list1[0]
    for i in list1:
        if i>maximum:
            maximum=i
    return maximum


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
![output](./Web%20capture_19-1-2023_13910_lms.ai.saveetha.ac.in.jpeg)
![output](./Web%20capture_19-1-2023_13926_lms.ai.saveetha.ac.in.jpeg)

## Output:
![output](./P1.png)
![output](./P2.png)
![output](./P3.png)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.