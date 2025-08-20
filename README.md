# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1:Import the numpy module to use the built-in functions for calculation
## Step 2:Prepare the lists from each linear equations and assign in np.array()
## Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
## Step 4: End the program

## Program:

```
#Program to find the eigen values and eigen vectors.
#Developed by: B.VIMALRAJ
#RegisterNumber:212224230304
import numpy as np
A=np.array([[2,2],[1,3]])
values,vector=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vector)

```
## Output:

<img width="895" height="690" alt="Screenshot 2025-08-20 114530" src="https://github.com/user-attachments/assets/4b283e0f-0176-4a1a-bae7-0dd34d15a3be" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
