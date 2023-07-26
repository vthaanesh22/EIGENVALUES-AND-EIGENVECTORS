# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use in build-in function for calculation 
### Step 2:
prepare the list from each linear equation and assign in np.array() 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: V.Thaanesh
#RegisterNumber:23003843
import numpy as np
arr=np.array([[2,2],[1,3]])
values,vector=np.linalg.eig(arr)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vector))
```
## Output:
![output](/Screenshot%202023-07-26%20130633.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
