# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Formulate the Characteristic Equation 
### Step 2: Solve for Eigenvalues and Find Eigenvectors
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Normalize Eigenvectors (Optional)

## Program:
```
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vector=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vector))
```
## Output:
![Screenshot (196)](https://github.com/user-attachments/assets/106ace61-c875-47d9-a3ad-7fc6aa62ee88)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
