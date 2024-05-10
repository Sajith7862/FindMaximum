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
#Program to mark the maximum of marks using the list method sort.
#Program developed by : MOHAMED HAMEEM SAJITH J
#Register num:212223240090
def max_marks(a):
    a.sort()
    return a[9]
```

ii)	# To find the maximum marks using the list method max().
```Python
#program to find the maximum marks using the list method max().
#Program developed by : MOHAMED HAMEEM SAJITH J
#Register num:212223240090
def max_marks(a):
    return max(a)
```

iii) # To find the maximum marks without using builtin functions.
```Python
#program to find the maximum marks without using builtin functions.
#Program developed by : MOHAMED HAMEEM SAJITH J
#Register num:212223240090
def max_marks(a):
    max =a[0]
    for i in a:
        if(i>max):
            max=i
    return max
```

## Output:
i)
![image](https://github.com/Sajith7862/FindMaximum/assets/145972360/590049c2-6fe6-4f97-8eeb-5acdb1d294ca)

ii)
![image](https://github.com/Sajith7862/FindMaximum/assets/145972360/08ade027-1d1c-4a01-9ac9-14e58428f4d4)

iii)
![image](https://github.com/Sajith7862/FindMaximum/assets/145972360/39a236d7-8bf5-45bd-9d89-01e1f264dfc3)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
