# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
import numpy module
### Step 2:
 initialize array using numpy
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
 end the program

## Program:
```python
#Developed by: Ragul R
#Register no.: 22003877
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```

## Output:
![Ragul1](https://user-images.githubusercontent.com/121609342/215526188-a6fc05d8-a1cb-4251-b2a7-4932e448b2ea.png)
![Ragul2](https://user-images.githubusercontent.com/121609342/215526429-81a19ab0-72c2-4c94-b80c-1f1f985211be.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
