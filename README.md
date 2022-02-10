# Inverse-of-matrix

## AIM:
To write a python program to find the inverse of a nested array.

## ALGORITHM:
### Step 1:
To import numpy as np 
### Step 2:
Create a two list and entry the two matrix using for loop.
### Step 3:
Add the number in list1 and list1 added to list2.
### Step 4:
Inverse the martrix.
### Step 5:
Print the inverse of the matrix.

## PROGRAM:
```
# Developed by: NITHISHWAR S
# Reference no: 21002766

import numpy as np
list1, list2 = [],[]
m1,m2= int(input()),int(input())
for i in range(m1):
    for j in range(m2):
        num=int(input())
        list1.append(num)
    list2.append(list1)
    list1=[]
print(list2)
value1= np.array(list2)
inverse = np.linalg.inv(value1)
print(inverse)
```
## OUTPUT:

## RESULT:
The above program is successfully find the inverse of the nested array.
