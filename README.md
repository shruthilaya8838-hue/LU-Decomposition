# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Write the python program for the given matrix.
2. Using the numpy library.
3. Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
4. Run the code and get the output.

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
X=lu_solve((lu,pivot),B)
print(X)
```

## Output:
<img width="1221" height="598" alt="Screenshot 2026-02-05 143125" src="https://github.com/user-attachments/assets/30b389cf-5247-4c98-bd41-80932c9d1364" />

<img width="1237" height="352" alt="image" src="https://github.com/user-attachments/assets/bfe18426-de90-4cc6-8a29-b1544452d35f" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

