# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import libraris
2. get the matrix from the user
3. find L and U
4. print the solution

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: MARXIN LIJO M
RegisterNumber: 23013468
*/
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
Developed by: MARXIN LIJO M
RegisterNumber: 23013468
*/
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)

```

## Output:
![image](https://github.com/MARXINLIJO/LU-Decomposition/assets/145742540/cc743694-0f5e-4fde-8ebe-9b893a8c1a51)
![image](https://github.com/MARXINLIJO/LU-Decomposition/assets/145742540/8f9af7e1-a4b9-4557-ba0d-7d2e2586c855)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

