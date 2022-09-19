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

Program to mark the maximum of marks using the list method sort
Developed by:Alagu Nachiyar k
RegisterNumber: 22002084


i)	To find the maximum of marks using the list method sort.

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



ii)	To find the maximum marks using the list method max().

def max_marks(marks):
    large=max(marks)
    return large


iii) To find the maximum marks without using builtin functions.

def max_marks(list1):
    max1=list1
    for i in list1:
        if i>max1:
            max1=i
    return max1




## Output:
### The maximum of marks using the list method sort.
![output 1](./![output1](https://user-images.githubusercontent.com/113497340/190955180-91d86680-793d-4995-82be-f73f94c47cad.jpeg)


### The maximum marks using the list method max().
![output2](./![output1](https://user-images.githubusercontent.com/113497340/190955326-3ca51bc3-5975-45d5-9451-32a34b8e9e1f.jpeg)



### The maximum marks without using builtin functions.
![output3](./![output3](https://user-images.githubusercontent.com/113497340/190955292-91102980-ed3e-4a0d-a2e3-6a9925ae00a4.jpeg)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
