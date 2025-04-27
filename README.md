# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Define the matrix A for which you want to find eigenvalues and eigenvectors.
### Step 2: Use NumPy's built-in function.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print or return the eigenvalues and eigenvectors separately.

## Program:
```
import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {} ".format(values,vectors))
 ```
## Output:
![Screenshot 2025-04-27 160427](https://github.com/user-attachments/assets/e12686f0-1877-4fc1-a842-abdaab80dd4a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
