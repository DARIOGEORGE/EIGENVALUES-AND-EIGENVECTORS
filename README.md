# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy as np
### Step 2: 
using array function convert the equation into matrix form .
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix. 
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: G DARIO
#RegisterNumber:22008843

import numpy as n
a=n.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=n.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:

![exp](https://user-images.githubusercontent.com/118704873/209906051-acdd94bc-85a5-43b3-99be-68f00d5b5d40.png)

![got](https://user-images.githubusercontent.com/118704873/209906065-5867802e-c72e-4d91-95ff-52199b9c2a51.png)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
