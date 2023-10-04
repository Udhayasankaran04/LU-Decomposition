# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.import numpy package.
2.import scipy package and use linalg function from lu.
3.Using three(P,L,U) variables store lu(arr).
4.print L and U.
5.End the program.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: M UDHAYA SANKARAN 
RegisterNumber: 212222110051
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
Developed by: 
RegisterNumber: 
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
## 1
![image](https://github.com/Udhayasankaran04/LU-Decomposition/assets/119393933/24605809-538a-460a-94ec-1947ed069079)

## 2
![image](https://github.com/Udhayasankaran04/LU-Decomposition/assets/119393933/64d382d5-c59c-43f2-aecf-d7d5300558d1)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
