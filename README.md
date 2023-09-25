# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np
2. Form scipy package import lu
3. Get input from the user 
4. Print Result 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: G Harish 
RegisterNumber: 23000630
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
Program to find the LU Decomposition of a matrix.
Developed by: G Harish
RegisterNumber: 23000630
import numpy as np
from scipy.linalg import lu_factor ,lu_solve 
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv,),b)
print(x)
*/
```

## Output:

![lu decomposition](https://github.com/Harish2404lll/LU-Decomposition/assets/141472096/278baa48-0b8c-4bbd-b8a9-ebfc3791a858)
![lu decompsition](https://github.com/Harish2404lll/LU-Decomposition/assets/141472096/535a0e50-82b0-4340-8e08-d900c7620bdc)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

