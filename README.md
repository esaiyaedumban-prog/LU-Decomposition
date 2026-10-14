# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm: LU Decomposition 
### 5.a
### 1. Start the program and import the required python libraries
### 2. Read the input matrix and initialize the L and U 
### 3. Calculate the L and U matrices using the LU Decomposition method 
### 4. Display the L and U matrices and stop the program
### 5.b
### 1. Start the program and import the required python libraries
### 2. Read the input matrix and initialize the L and U 
### 3. Calculate the L and U matrices using the LU Decomposition method 
### 4. Display the L and U matrices and stop the program

### Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: ESAIYA E
RegisterNumber: 26014140
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
### program:
(ii) To find the LU Dem composition of the matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: ESAIYA E 
RegisterNumber: 26014140
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
*/
```

### Output:
![lu decomposition]()
### 5.a
<img width="1082" height="837" alt="Screenshot 2026-10-14 095135" src="https://github.com/user-attachments/assets/5c3d9cac-3187-4674-834f-c98972ae919d" />

### 5.b
 <img width="982" height="765" alt="Screenshot 2026-10-14 095159" src="https://github.com/user-attachments/assets/f7dd19df-9a05-4e66-8e48-9186b56921df" />
 
 Result:
 Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

