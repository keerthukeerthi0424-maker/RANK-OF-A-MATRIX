# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: import the NumPy module to use the built in function for calculation 
### Step 2: create the given matrix using np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:
# ###Program to find the rank of a matrix.
# ###Developed by: Keerthana T A
# ###RegisterNumber:26009041
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[1,2,3],[3,6,9]])
sol=np.linalg.matrix_rank(a)
print(sol)
## Output:
<img width="867" height="732" alt="image" src="https://github.com/user-attachments/assets/cbd76784-c7d5-436c-a222-f3b1290d6c13" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

