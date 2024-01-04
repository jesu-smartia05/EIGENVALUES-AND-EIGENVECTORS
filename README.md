# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy package
### Step 2: 
Get the input matrix
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print the code.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: JESU SMARTIA A
#RegisterNumber:212223110016
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output

![Screenshot 2024-01-04 060030](https://github.com/jesu-smartia05/EIGENVALUES-AND-EIGENVECTORS/assets/148514819/9c2f13a5-8bb3-4c62-a903-c984be2b824f)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
