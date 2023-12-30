# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
#To print L and U matrix
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
Developed by: 
RegisterNumber: 
*/
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```

## Output:
![lu decomposition]()
![WhatsApp Image 2023-12-31 at 02 20 55_6d0ea735](https://github.com/ibrahimfedahs/LU-Decomposition/assets/150319493/99c29ecc-4b09-4080-bcb4-7dbaa34cf744)
![WhatsApp Image 2023-12-31 at 02 21 27_58c3ee4f](https://github.com/ibrahimfedahs/LU-Decomposition/assets/150319493/23c30ac2-936e-4208-abcc-b0ed3307b5aa)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

