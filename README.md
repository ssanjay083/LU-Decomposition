# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.

2. Get input from user and print L and U matrix by 'print' .

3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable

4. print the variable 'X'


## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by:  Sanjay S
RegisterNumber: 212224110047
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U) 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: Sanjay S
RegisterNumber: 212224110047
'''

# To print X matrix (solution to the equations)

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
*/
```

## Output:
<img width="1700" height="959" alt="image" src="https://github.com/user-attachments/assets/653ad3e9-b9e1-490e-85a5-0c46b2a0c3c0" />

<img width="1717" height="771" alt="image" src="https://github.com/user-attachments/assets/6fb98df7-19e2-4c1b-908f-a84c899c608a" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

