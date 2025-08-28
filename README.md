# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'print' .
3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable
4.print the variable 'X'

## Program:
```
(i) To find the L and U matrix
'''Program to find L and U matrix using LU decomposition.
Developed by: Mukesh raj
RegisterNumber: 212224100038
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```Program to solve a matrix using LU decomposition.
Developed by:Mukesh raj  
RegisterNumber: 212224100038
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
```


## Output:

<img width="1920" height="1080" alt="MFA EXP-5a" src="https://github.com/user-attachments/assets/afc92f78-f8e6-4098-b59a-6968d6bb930a" />
<img width="1920" height="1080" alt="MFA EXP-5b" src="https://github.com/user-attachments/assets/64df868a-0050-49ee-b48d-2d4682647e9b" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

