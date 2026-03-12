## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation
2. Prepare the lists from each linear equations and assign in np.array()
3.Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
4.End the program

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```


import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot= lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```
Program to solve a matrix using LU decomposition.


Developed by: vishwa.s
RegisterNumber: 25012636


## Output:

<img width="991" height="745" alt="image" src="https://github.com/user-attachments/assets/f0c58159-84e3-4096-b80d-4277076ba9d8" />
<img width="1290" height="751" alt="image" src="https://github.com/user-attachments/assets/e57e178e-c1d3-470e-8b8c-4b865940160e" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

