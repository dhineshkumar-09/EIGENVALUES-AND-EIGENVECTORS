# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy as np.
### Step 2: Assign np.array() in eigen values and eigen vectors.
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print both the values and vectors, then end the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:DHINESHKUMAR E
#RegisterNumber:212224220026
import numpy as np
a=np.array( [[4,2],[2,4]])
b,c=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(b,c))
```

## Output:

![image](https://github.com/user-attachments/assets/91925747-11a9-4459-8b88-e0b013042279)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
