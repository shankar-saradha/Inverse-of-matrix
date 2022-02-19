# Inverse-of-matrix

## AIM:To write a program to perform Inverse-of-matrix using python programming.

## ALGORITHM:
### Step 1:
Import Numpy module as np
### Step 2:
Create empty lists.
### Step 3:
Get input from the user for number of rows and columns.
### Step 4:
Use nested lists to append list.
### Step 5:
Print the inverse of the array using np.linalg.inv .


## PROGRAM:
~~~
import numpy as np
z, y= [],[]
a, b= int(input()),int(input())
for i in range(a):
    for j in range(b):
        num=int(input())
        z.append(num)
    y.append(z)
    z=[]
print(y)
var1= np.array(y)
inv = np.linalg.inv(var1)
print(inv)
~~~

## OUTPUT:
![inverse of a matrix ](https://user-images.githubusercontent.com/93978702/154786792-15e715b9-f4b2-4377-9f87-1096ab387b19.png)

## RESULT:
Thus the program is written to perform Inverse-of-matrix using python programming.
