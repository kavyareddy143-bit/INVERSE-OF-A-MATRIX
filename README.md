# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array()

Step 3:
Using np.linalg.inv(),we can find the inverse of a matrix

Step 4:
End the program

## Program:
```
Program to find the inverse of a matrix.
#Developed by:Annapureddy kavya 
#RegisterNumber:212225240011
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixA=np.array([[6,2,3],[3,1,1],[10,3,4]])
result=np.linalg.inv(matrixA)
print(result)
```
## Output:
<img width="1052" height="821" alt="image" src="https://github.com/user-attachments/assets/a6fc00ae-a65a-481c-870f-34a316531e3f" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

