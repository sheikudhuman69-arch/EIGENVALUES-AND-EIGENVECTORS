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
End The Program
## Program:
import numpy as np
A=np.array([[2,2],[1,3]])
X,Y=np.linalg.eig(A)
print("Eigen values are",X, "and", "Eigen Vectors are",Y)
## Output:

<img width="1920" height="1080" alt="Screenshot 2025-11-19 113951" src="https://github.com/user-attachments/assets/8a4a6607-cdf1-44a1-bb6d-ad9ffd31b311" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
