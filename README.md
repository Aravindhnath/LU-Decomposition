# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. step 1
Import the numpy module to use the built-in functions for calculation
2. step 2
Prepare the lists from each linear equations and assign in np.array()
3. step 3
Using the np.linalg.solve(), we can find the solutions.
4.step 4
End the program

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by:  aravindhnath
RegisterNumber:  22009024
import numpy as np
from scipy.linalg import lu
A= np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: aravindhnath
RegisterNumber:  22009024
import numpy as np
from scipy.linalg  import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:

![ara](https://user-images.githubusercontent.com/118790841/212035520-ea82f43e-8772-495a-a9d8-dfe456a07cec.png)

![ara 2](https://user-images.githubusercontent.com/118790841/212035530-b0957d60-80dc-4139-9dc6-72fed14a8704.png)

## Result:
Thus the solutions for the LU decomposition are successfully solved using python progra

