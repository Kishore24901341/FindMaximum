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
```
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large



```

ii)	# To find the maximum marks using the list method max().
```
def max_marks(marks):
    large = max(marks)
    return large
    

```

iii) # To find the maximum marks without using builtin functions.
```
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max        



```



## Output:
![image](https://github.com/user-attachments/assets/bce982d2-40e7-4b40-9acc-efb81a15c9d1)
![image](https://github.com/user-attachments/assets/4004c21f-83e4-4f16-8005-8e336137f3af)
![image](https://github.com/user-attachments/assets/7746c35c-9117-4f9a-8e78-9369b62b9592)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
