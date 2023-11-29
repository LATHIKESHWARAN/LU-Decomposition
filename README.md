# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy.linalg import lu,lu_factor,lu_piv
3. Get input from the user as eval(input())
4. Use lu_factor and lu_solve to find LU decomposition
5. print L,U
6. print x

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Lathikeshwaran J
RegisterNumber: 212222230072
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Lathikeshwaran J
RegisterNumber: 212222230072
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![image](https://github.com/LATHIKESHWARAN/LU-Decomposition/assets/119393556/0abe0950-eba1-4057-89d8-ffe5f29b7a23)

![Screenshot 2023-11-29 205058](https://github.com/LATHIKESHWARAN/LU-Decomposition/assets/119393556/a6721ed7-b7ab-4f89-ba77-80328d79d33d)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

