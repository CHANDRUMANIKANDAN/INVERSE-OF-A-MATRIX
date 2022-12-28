# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: CHANDRU M
#RegisterNumber:22009010
import numpy as np
A = np.array([[2,1,1],[1,1,1],[1,-1,2]])
B = np.linalg.inv(A)
print(B)
```
## Output:![Screenshot_20221228_070125](https://user-images.githubusercontent.com/118644502/209819970-6d1f8919-261b-4a1a-8ed3-42845d83a828.png)

## Result:
Thus the inverse of given matrix is successfully solved using python program

