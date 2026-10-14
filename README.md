# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import os and numpy 
### Step 2: create an square matrix a as a numpy array 
### Step 3:compute the inverse of a using numpy.linalg.inv(a) and store in b
### Step 4: print the result

## Program:import os

os.environ["OPENBLAS_NUM_THREADS"]= "1"

import numpy

a=numpy.array([[2,1,1],[1,1,1],[1,-1,2]])

b=numpy.linalg.inv(a)

print(b)


## Output:<img width="1022" height="739" alt="{963096B9-7243-4A4E-8072-F7FB1EB93A88}" src="https://github.com/user-attachments/assets/860e2579-d167-4dd3-a51d-5cf6409b0b99" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

