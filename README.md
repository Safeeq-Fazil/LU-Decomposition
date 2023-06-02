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
```
/*
Program to find the L and U matrix.
Developed by: Safeeq Fazil.A
RegisterNumber: 212222240086
*/

import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Safeeq Fazil.A
RegisterNumber: 212222240086
*/


# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=np.array([4, 5, 7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)

```

## Output:
## find the L and U matrix:
![exp 5](https://github.com/Safeeq-Fazil/LU-Decomposition/assets/118680361/ed3f722a-e595-4a96-b0b0-171bcfb9f298)

## find the LU Decomposition of a matrix:
![lu decomposiyion b](https://github.com/Safeeq-Fazil/LU-Decomposition/assets/118680361/b34baa9c-bc2c-4f5d-8bbf-e18e585f1998)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

