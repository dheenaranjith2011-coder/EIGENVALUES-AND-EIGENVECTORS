# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :import numpy(array format) as np 
### Step 2: place the given matrix in the program
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print it to get result

## Program:
```
import numpy as np
matrix=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eig_values,eig_vector=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_values,eig_vector))

```

## Output:
![output](<Screenshot 2026-02-12 093328.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
