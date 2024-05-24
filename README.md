# EX:4 EIGENVALUES-AND-EIGENVECTORS
Date:23-03-2024
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
 importing the NumPy library.
### Step 2: 
Define the given matrix A.
### Step 3: 
 Use np.linalg.eig(A) to find the eigenvalues and eigenvectors.
### Step 4: 
print and end the program.
## Program:
```
#Developed by:Shanthosh.G
#Register Number:2305003008

import numpy as np
A = np.array([[2,2],[1,-3]])
values,vector = np.linalg.eig(A)
print("Eigenvalues are {} and Eigenvectors are {} ".format(values,vector))
```
## Output:
![Screenshot 2024-04-19 223055](https://github.com/shanthosh397/EIGENVALUES-AND-EIGENVECTORS/assets/153431200/d55d7151-a674-426e-af73-bab2852106a1)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
