# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built in functions for calculations .
### Step 2: 
Prepare the lists from each equation and assign an np.array 
### Step 3: 
using the np.linalg.matrix_rank(),we can find the inverse of the given matrix .
### Step 4: 
End the program .
## Program:
#Program to find the inverse of a matrix.
#Developed by: NAKUL R
#RegisterNumber: 212223240102
import numpy as np
matrix=np.array(([[1,0,3],[-1,2,-2],[2,3,-1]]))
result=np.linalg.inv(matrix)
print(result)
## Output:
![Screenshot 2024-04-15 191611](https://github.com/Nakul1411/INVERSE-OF-A-MATRIX/assets/138849780/2ef7b923-55a7-4692-86d6-3a03e321eee3)

## Result:
Thus the inverse of given matrix is successfully solved using python program

