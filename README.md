# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy
### Step 2: get input form the user
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the desire output

## Program:
```
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigenvalues,eigenvectors=np.linalg.eig(A)
print("Eigen values are",eigenvalues,"and Eigen Vectors are",eigenvectors)

```
## Output:
![image](https://github.com/user-attachments/assets/93cfaf0d-ddeb-4a47-8fab-b5e1a41da134)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
