# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import Numpy module and lu library from scilig modules
2. Declare the array
3. Using lu library calculate the Lower triangle matrix and upper triangle matrix
4. End the program

## Program:
(i) To find the L and U matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: Athul Krishna A V
RegisterNumber: 25013602
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
<img width="1208" height="803" alt="image" src="https://github.com/user-attachments/assets/a7ddb299-ff42-44b4-b4f8-1d262a8d3fff" />

(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Athul Krishna A V
RegisterNumber: 25013602
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)


```
<img width="1207" height="778" alt="image" src="https://github.com/user-attachments/assets/e06ffe27-2f76-47be-a859-8216ff67e82e" />

## Output:
i)
<img width="1211" height="508" alt="image" src="https://github.com/user-attachments/assets/a3121832-1f01-4f64-91c0-8536b8d7e759" />
<br>
ii)
<img width="1211" height="271" alt="image" src="https://github.com/user-attachments/assets/05c7859e-f837-43e6-9dd6-7cf8c7a60930" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

