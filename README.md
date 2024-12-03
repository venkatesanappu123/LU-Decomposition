# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
   1.To Find L and U matrices with LU Decomposition
1.  Get the matrix from the user.
2.  Using "from scipy.linalg import lu" to import scipy (LU) module.
3.  Using "L,U=lu(a)" we can get the matrix of L and U.
4.  Print the result matrices (L and U Matrices).
5.  End of the Program.
   
   2.To Find X matrix with LU Decomposition
  
1.  Get the matrix from the user.
2.  Using "from scipy.linalg import lu_factor,lu_solve" to import scipy module for factorization and solving X.
3.  Using "lu,piv=lu_factor(a)"
4.  Print the output(x matrix)
5.   End of the Program.


## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: Venkatesan R
RegisterNumber: 24900061

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
p,l,u=lu(A)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: Venkatesan R
RegisterNumber: 24900061

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![Screenshot 2024-12-03 132752](https://github.com/user-attachments/assets/8446dc7c-e5af-48c8-a806-32b4224503af)

![Screenshot 2024-12-03 132818](https://github.com/user-attachments/assets/1136d76e-1aba-493b-aea5-55849ea9f293)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

