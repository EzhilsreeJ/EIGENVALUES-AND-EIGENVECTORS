# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2:
 Prepare the lists from each linear equations and assign in np.array() 
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```py
#Program to find the eigen values and eigen vectors.
#Developed by:Ezhil sree J
#RegisterNumber:23012968
import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![image](https://github.com/EzhilsreeJ/EIGENVALUES-AND-EIGENVECTORS/assets/144870412/cb9ad756-7015-4667-ae51-5d46e3ea0651)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
