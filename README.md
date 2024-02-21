# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
we have imported numpy which is needed.

### Step 2: 
we have created a matrix using np.array with different values in it.

### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
finally,print the values of the eigen values and eigen vectors.

## Program:
Developed by: RITHISH P

RegisterNumber:212223230173

import numpy as np

A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])

values,vectors=np.linalg.eig(A)

print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

## Output:
![image](https://github.com/RITHISHlearn/EIGENVALUES-AND-EIGENVECTORS/assets/145446645/7072462f-01d9-4fe7-89fd-37c33b177e25)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
