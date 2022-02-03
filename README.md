# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Get the matrix from the user.

### Step 2: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.

### Step 3: 
Print the two results (Eigen values and Eigen vectors).

### Step 4: 
End of the program. 

## Program:
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(A)
print(rank)

## Output:
![GitHub Logo](matrix.jpg)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

