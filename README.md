# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' .
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4.print the variable 'X'


## Program:
```i) '''
Program to find L and U matrix using LU decomposition.
Developed by: PAVITHRAN MJ
RegisterNumber: 212223240112'''

import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
```
ii)'''Program to solve a matrix using LU decomposition.
Developed by: PAVITHRAN MJ
RegisterNumber: 212223240112'''

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv = lu_factor(a)
x= lu_solve((lu,piv),b)
print(x)
```

## Output:
![Screenshot 2024-04-16 194630](https://github.com/Pavithranmurugan13/LU-Decomposition/assets/163802201/82016660-36a5-4ba1-94fe-7bb1e3b51c96)

![Screenshot 2024-04-16 194650](https://github.com/Pavithranmurugan13/LU-Decomposition/assets/163802201/fdf4af5f-d022-4ed2-a295-4fea1e270022)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

