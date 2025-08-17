# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from the matrix and assign in np.array()

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
End the program.

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: Jayaharshini s
#RegisterNumber:212224100024
import numpy as np
A = np.array([[4,2],[2,4]])
B,C = np.linalg.eig(A)
print(f"Eigen values are {B} and Eigen Vectors are {C}")

## Output:
<img width="1895" height="992" alt="Screenshot 2025-08-17 220918" src="https://github.com/user-attachments/assets/66c5411c-f632-44ac-80af-5390bde1a389" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
