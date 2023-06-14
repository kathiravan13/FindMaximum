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
Developed by: kathiravan.p
RegisterNumber: 212222230063
'''
def max_marks(marks):
    marks.sort()
    large = max(marks)
    return large
    

```

ii)	# To find the maximum marks using the list method max().
```Python

''' 
Program to find the maximum marks using the list method max().
Developed by: kathiravan.p
RegisterNumber: 212222230063
'''
def max_marks(marks):
    # write your code here
    large = max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by :kathiravan
RegisterNumber:212222230063  
'''
def max_marks(list1):
    # write your code here
    max = list1[0]
    for i in list1:
        if i > max:
            max = i

    return max
    


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![2023-06-14](https://github.com/kathiravan13/FindMaximum/assets/119831303/d4280ff9-eaab-4e9b-9b4e-d5551a3d2688)
![2023-06-14 (1)](https://github.com/kathiravan13/FindMaximum/assets/119831303/a5a2cdf3-adc7-443f-a24f-db260405525e)
![2023-06-14 (2)](https://github.com/kathiravan13/FindMaximum/assets/119831303/435d8111-a618-4797-9c60-6082fff00f37)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
