# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import the numpy module to use the built-in functions for calculation
### Step 2: 
prepare the lists from each linear equations and assign in no.array().
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
end the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: LEVAKU LAKSHMI MOUNIKA
#RegisterNumber:23004124
import numpy as np
a=[[4,2],[2,4]]
Values,vectors=np.linalg.eig(a)
print("Eigen values are",Values,"and Eigen Vectors are",vectors)
## Output:
![Screenshot 2023-11-26 141549](https://github.com/mounika2005/EIGENVALUES-AND-EIGENVECTORS/assets/145633112/a2b073d7-c540-4d1a-b5e8-c0737590b919)
```
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
