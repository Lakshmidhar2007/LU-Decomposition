# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module, scipy module to use the built-in functions for calculations.

2. Prepare the lists from each linear equations and assign in np.array().

3. Using the Built-in functions such as lu(), lu_factor(), lu_solve() find the L, U, LU decomposition of the matrix

4. End the program

## Program:
(i) To find the L and U matrix
```

Program to find the L and U matrix.
Developed by: LAKSHMIDHAR  N
RegisterNumber: 24900046

PROGRAM:

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P, L, U = lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: LAKSHMIDHAR  N
RegisterNumber: 24900046

PROGRAM:

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu,piv),b)
print(x)


```

## Output:
![Lu decomposition](<mat exp - 5 ans.png>)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

