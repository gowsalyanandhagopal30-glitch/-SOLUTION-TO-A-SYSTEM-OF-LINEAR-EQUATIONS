# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by:N.GOWSALYA 
#RegisterNumber:25016458
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B=np.array([-9,4,-1])
X=np.linalg.solve(A,B)
print(X)
```
## Output:

<img width="1920" height="1080" alt="Screenshot (47)" src="https://github.com/user-attachments/assets/0ecd9db1-3917-48f6-970e-4acdbdd511b5" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

