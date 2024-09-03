# DATE :
# EXP 03 : INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the inverse of the given matrix
### Step 4: 
End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: Sree Niveditaa Saravanan
#RegisterNumber: 212223230213
```
```
import numpy as np
a = np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
c = np.linalg.inv(a)
print(c)
```
## Output:

![image](https://github.com/user-attachments/assets/63b59bd9-5878-4d0a-8355-e44648a46845)

![image](https://github.com/user-attachments/assets/2c3cf284-3522-448b-9bfe-324a52ba1c1e)


## Result:
Thus the inverse of given matrix is successfully solved using python program

