# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
we have to initialise program using import numpy to perform mathematical calculation.
### Step 2: 
The input from the user is stored in the variable a.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: G.Chethan Kumar
#RegisterNumber: 212222240022

import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
evalues,evectors=np.linalg.eig(A)
print("Eigen values are {0} and Eigen Vectors are {1}".format(evalues,evectors))
```
## Output:

![Screenshot 2023-04-27 062255](https://user-images.githubusercontent.com/118348224/234732584-667d888f-0d5e-4e37-afee-3d529210a32b.png)


## Result:

Thus the Eigenvalue and Eigenvector is successfully solved using python program
