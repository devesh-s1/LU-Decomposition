## LU Decomposition
AIM:
To write a program to find the LU Decomposition of a matrix.

Equipments Required:
Hardware – PCs
Anaconda – Python 3.7 Installation / Moodle-Code Runner
Algorithm
Import numpy and scipy packages.
Read the input matrix as two dimensional array
Call the Built in function lu() to decompose the array.
print the output.
Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: S Devesh Sharma
RegisterNumber: 22005350
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: S Devesh Sharma
RegisterNumber: 22005350
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv), b)
print(x)
*/
```
##Output:
![LC](https://user-images.githubusercontent.com/121490523/215439855-94548187-f543-4914-9824-9cb9da8c2ee2.png)

Result:
Thus the program to find the L and U Decomposition and LU Decomposition of a matrix are written and verified using python programming.
