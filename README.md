# Multiplying-two-matrix

## AIM:To write a python program for multiplying two matrix.

## ALGORITHM:

Step 1:
Import Numpy as np.

Step 2:
Get input from the user.

Step 3:
Create empty lists l1 and l2.

Step 4:
Use for loop to append the values into the list created.

Step 5:
Print the product of two arrays.


## PROGRAM: 
~~~
import numpy as np
array1 = []
array2 = []
n= int(input())
for i in range(n):
    array1.append(int(input()))
for i in range(n):
    array2.append(int(input()))
value1= np.array(array1)
value2= np.array(array2)
result = value1*value2
print("Product of two arrays is:",result)

## OUTPUT:
~~~
![VUI](https://user-images.githubusercontent.com/94883079/154828877-1ec23ab0-40eb-4f05-bddc-132a59fda76c.png)


## RESULT:Thus the program is written to multiply two matrix.

