<img width="564" height="433" alt="Screenshot 2025-09-02 142934" src="https://github.com/user-attachments/assets/815a65bb-1f8e-4b41-85cf-d46254ea20de" /># -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
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
#Developed by: Saravana Kumar S
#RegisterNumber:212224220090

import numpy as np
A=np.array([[1,3],[2,5]])
B=np.array([5, -3])
C=np.linalg.solve(A,B)
print(C)
```


## Output:
<img width="564" height="433" alt="Screenshot 2025-09-02 142934" src="https://github.com/user-attachments/assets/7751b571-74c0-4707-bdab-ad2e770b4012" />


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

