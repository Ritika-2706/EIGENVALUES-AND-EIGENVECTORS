# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Commence the program
### Step 2: Enter the matrix by importing numpy
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the result and stop the program

## Program:
import numpy as np
a=np.array([[2,2],[1,3]])
values,Vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are", Vectors)

## Output:
![image](https://user-images.githubusercontent.com/93427238/154842597-898ea57a-b4c4-4e14-895d-43cc5daa3d9d.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
