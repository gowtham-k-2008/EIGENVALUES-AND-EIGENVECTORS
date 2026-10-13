# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Read the input values.
### Step 2: Import the required packages.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the results.

### Program: #Program to find the eigen values and eigen vectors.
### Developed by: GOWTHAM.K
### RegisterNumber: 26014578

### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### A=np.array([[4,2] , [2,4]])
### values,Vectors = np.linalg.eig(A)
### print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))

### Output: <img width="1305" height="759" alt="Screenshot 2026-10-13 222153" src="https://github.com/user-attachments/assets/bb93878e-b936-4226-b8f3-51fb46bba4f7" />

### Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
