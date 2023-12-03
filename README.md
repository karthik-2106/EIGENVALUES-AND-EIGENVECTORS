# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation.
### Step 2:
Enter the given matrix lists and assign it to a variable. 
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program. 

## Program:
``````
#Program to find the eigen values and eigen vectors.
#Developed by: KARTHIKEYAN M
#RegisterNumber:23005191
import numpy as np
a=[[2,2],[1,3]]
b,c=np.linalg.eig(a)
print("Eigen values are",b,"and Eigen Vectors are",c)
``````
## Output:
![OUTPUT](/Screenshot%202023-12-03%20174420.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
