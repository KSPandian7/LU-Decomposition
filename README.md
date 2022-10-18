# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

Step 1: Import numpy library using import statement.

Step 2: From scipy package import lu().

Step 3: Get input from user and pass it as an array.

Step 4: Get P, L, U matrix using lu()

Step 5: Print L and U matrix

## Program:
(i) To find the L and U matrix
```py
Program to find L and U matrix using LU decomposition.
Developed by: kulasekarapandian
RegisterNumber: 22001410

# To print L and U matrix
import numpy as np
from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```py
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu, piv=lu_factor(a)
x=lu_solve((lu, piv),b)
print(x)
```
## Output:
![output](/op1lu.png)


![output](/op2lu.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

