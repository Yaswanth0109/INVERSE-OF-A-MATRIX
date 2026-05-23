# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: End the program

## Program:
#Program to find the inverse of a matrix.
#Developed by: YASWANTH V
#RegisterNumber:25010248
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([
    [1,0,3],
    [-1,2,-2],
    [2,3,-1]])
soln=np.linalg.inv(A)
print(soln)
## Output:
<img width="1072" height="859" alt="image" src="https://github.com/user-attachments/assets/0e93d81e-1bfb-4cd2-baf8-f1ded8e71427" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

