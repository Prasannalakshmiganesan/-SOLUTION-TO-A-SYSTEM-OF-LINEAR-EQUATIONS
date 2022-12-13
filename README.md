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
``` python
import numpy as np 
a = np.array([[1,-3],[3,1]])
b = np.array([0,10])
solution = np.linalg.solve(a,b)
print(solution)
```

## Output:![exp output 1](https://user-images.githubusercontent.com/118610231/207239085-b3da9d61-3f59-408d-8efd-f1fda922a22a.png)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

