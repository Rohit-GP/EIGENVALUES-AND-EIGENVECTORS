# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as np.
### Step 2: 
Assign np.array() in eigen values and eigen vectors.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print both the values and vectors, then end the program.

## Program:
Name : Rohit GP

Ref No : 24900185
```
import numpy as n

val,vec=n.linalg.eig(n.array([[2,2],[1,3]]))
print(f"Eigen values are {val} and Eigen Vectors are {vec}")
```
## Output:
![Screenshot 2025-05-21 133350](https://github.com/user-attachments/assets/b335851c-d848-4d4e-9879-674dba6f9ceb)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
