# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1:
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from each linear equations and assign in np.array()

Step 3:
Using the np.linalg.solve(), we can find the solutions.

Step 4:
End the program

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[2,1,1],[1,1,1],[1,-1,2]])
result=np.linalg.inv(a)
print(result)
```


## Output:
<img width="1039" height="270" alt="image" src="https://github.com/user-attachments/assets/8dee753c-02ef-45a1-ab57-c71c6ce541db" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

