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

import numpy as np

A=np.array([[1,3],[2,5]])

B=np.array([5,3])

result=np.linalg.slove(A,B)

print(result)


## Output:

![Screenshot (68)](https://github.com/Anusharonselva/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/119405600/9974ef2a-0537-4c12-84cf-0a945f7121e7)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

