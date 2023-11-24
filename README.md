# Find the maximum of a list of numbers
### NAME : ALIYA SHEEMA
### REFERENCE NUMBER : 23005529

## AIM :
To write a program to find the maximum of a list of numbers.

## EQUIMENT'S REQUIRED :

1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## ALGORITHM :

1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value

## PROGRAM :

i)	# To find the maximum of marks using the list method sort.
```
Program to mark the maximum of marks using the list method sort
Developed by: ALIYA SHEEMA
RegisterNumber: 23005529

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```



ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: ALIYA SHEEMA
RegisterNumber: 23005529

def max_marks(marks):
    large=max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: ALIYA SHEEMA
RegisterNumber: 23005529

def max_marks(list1):
    max=list1[0]
    for number in list1:
        if (number>max):
            max=number
    return max
```
## Sample Input and Output
![output](./img/max_marks1.jpg)

![Alt text](max_function.png)

![Alt text](max_without_fn.png)

## Output:

![Alt text](sort_output.png)

![Alt text](function_output.png)


![Alt text](without_fn_output.png)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.