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
Python
```
Program to mark the maximum of marks using the list method sort
Developed by: RITHVIK S
RegisterNumber: 212223100045

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```
ii)	# To find the maximum marks using the list method max().
```
Program to mark the maximum of marks using the list method sort
Developed by: RITHVIK S
RegisterNumber: 212223100045

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```
iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: KEERTHIVASAN M
RegisterNumber: 212223100021
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max=i
    return max
```
## Output:
![EXP 6 IMAGE](https://github.com/Rithviknathan/FindMaximum/assets/148410509/50e52542-d0ee-486d-8f2d-529776b2d33f)
![EXP 6 IMAGE 2](https://github.com/Rithviknathan/FindMaximum/assets/148410509/dfee3b48-54ea-4278-a3bf-23ae55575e8b)
![EXP 6 IMAGE 3](https://github.com/Rithviknathan/FindMaximum/assets/148410509/bcd36f17-4628-453a-bed5-fdd56e93064a)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
