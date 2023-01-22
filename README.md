# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy package import lu
3. get input from the user
4. print the result

## Program:
(i) To find the L and U matrix
```python
/*
Program to find the L and U matrix.
Developed by: SUDHAKAR K
RegisterNumber: 22007876
*/
import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
/*
Program to find the LU Decomposition of a matrix.
Developed by: SUDHAKAR K
RegisterNumber: 22007876
*/
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
```

## Output:
![sl1](https://user-images.githubusercontent.com/118622513/213903132-54698107-2af5-41e1-8cc2-67bc3e93edb4.png)
![sl2](https://user-images.githubusercontent.com/118622513/213903134-1d799172-eb7a-4d0d-9806-1e12d8c8f221.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

