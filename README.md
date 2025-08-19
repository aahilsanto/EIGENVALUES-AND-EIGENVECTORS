# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix
### Step 4: 
End the program

## Program:

Program to find the solution for the given linear equations.

Developed by: A Ahil Santo

RegisterNumber: 212224040018

```
import numpy as np
A=np.array([[2,2],[1,3]])
val,vet=np.linalg.eig(A)
print(f"Eigen values are {val} and Eigen Vectors are {vet}")
```


## Output:

<img width="1220" height="338" alt="image" src="https://github.com/user-attachments/assets/9319b6a3-0dcf-43a3-9c97-47b8d5df3973" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
