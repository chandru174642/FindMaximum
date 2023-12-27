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
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: CHANDRU.P
RegisterNumber: 23007250
'''
def max_marks(marks):
    b=len(marks)
    marks.sort()
    return marks[b-1]
    


```

ii)	# To find the maximum marks using the list method max().
```Python

''' 
Program to find the maximum marks using the list method max().
Developed by:CHANDRU.P 
RegisterNumber:23007250 
'''
def max_marks(marks):
    return max(marks)

```

iii) # To find the maximum marks without using builtin functions.
```Python

''' 
Program to the maximum marks without using builtin functions.
Developed by:CHANDRU.P 
RegisterNumber: 23007250
'''
def max_marks(list1):
    a=0
    for i in list1:
         if i>a:
             a=i
    return a         

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 
![Screenshot 2023-12-27 193636](https://github.com/chandru174642/FindMaximum/assets/139841798/af3344a1-7cd9-489d-a67c-dfef10c9e3f3)
![Screenshot 2023-12-27 193731](https://github.com/chandru174642/FindMaximum/assets/139841798/9eee93fe-60ca-4fce-aacf-025b29ad8175)
![Screenshot 2023-12-27 193742](https://github.com/chandru174642/FindMaximum/assets/139841798/7bcd7904-46b9-4007-9a9b-ccff82aa3b96)

## Output:

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
