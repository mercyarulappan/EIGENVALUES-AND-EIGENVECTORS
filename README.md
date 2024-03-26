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
Prepare the lists from the matrix and assign in np.array()
### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: MERCY A
#RegisterNumber: 212223110027

import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
b,c=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(b,c))

```
## Output:

![Screenshot 2024-03-26 173855](https://github.com/mercyarulappan/EIGENVALUES-AND-EIGENVECTORS/assets/149233730/dd91be12-3e37-4eb2-b3ef-edd06dc63a9b)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
