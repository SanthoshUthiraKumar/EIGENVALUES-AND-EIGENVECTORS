# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigen Values and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
### Step 1:
Import the library numpy using the import command.

### Step 2: 
Assigning a matrix to a variable.

### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
Print the eigen values and eigen vectors of the matrix and end the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Santhosh U
#RegisterNumber:22009224
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vector=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vector)
```
## Output:
![EigenOutput](https://user-images.githubusercontent.com/119477975/214599895-03f57970-c2cf-4d6a-b3c6-6c1bfd71b881.png)

## Result:
Thus the Eigenvalues and Eigenvectors are successfully solved using python program
