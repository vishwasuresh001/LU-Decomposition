# LU Decomposition 

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
/*
Program to find the L and U matrix.
Developed by: Vishwa.s

RegisterNumber: 255012636
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Vishwa.s
RegisterNumber: 25012636
*/
```
Program to solve a matrix using LU decomposition.
Developed by: vishwa.s

RegisterNumber: 25012636

```
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot= lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:
<img width="863" height="752" alt="image" src="https://github.com/user-attachments/assets/c1a3c378-69ab-41ab-b038-e4137ba3e811" />

<img width="781" height="599" alt="image" src="https://github.com/user-attachments/assets/5cb4e6c7-9f7e-4219-8576-01b060b0d162" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

