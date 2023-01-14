# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for
calculation

2.  Prepare the lists from each linear equations and assign in
np.array()

3. Using the scipy.linalg and imort lu_fator and lu_solve we get the values

4. End the program

## Program:
(i) To find the L and U matrix
'''Program to find L and U matrix using LU decomposition.
Developed by: Naveen M
RegisterNumber: 22000748
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)

(ii) To find the LU Decomposition of a matrix
'''Program to solve a matrix using LU decomposition.
Developed by: Naveen M
RegisterNumber: 22000748
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)

## Output:
![lu1](https://user-images.githubusercontent.com/117974950/212479444-d0f7533f-3d3c-403e-8cd0-1e64f9a0a28f.png)

![lu2](https://user-images.githubusercontent.com/117974950/212479499-db4ffd36-5601-4dfd-a1ab-6482b8783fa3.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

