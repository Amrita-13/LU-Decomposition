# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
```
Start the program
Import the necessary libraries(numpy,scipy.linalg)
Define the matrix using numpy
Use lu(),lu_solve(),lu_factor() to get the solutions
End the program
```
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Amrita B S
RegisterNumber:212225100002
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
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
Developed by: Amrita B S
RegisterNumber:212225100002
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
*/
```

## Output:
<img width="1243" height="872" alt="image" src="https://github.com/user-attachments/assets/e52519f5-57c5-4d14-92ae-22def2f3d3f4" />
<img width="1327" height="847" alt="image" src="https://github.com/user-attachments/assets/28c24dd2-2c15-468e-b7b2-06ef7590e06e" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

