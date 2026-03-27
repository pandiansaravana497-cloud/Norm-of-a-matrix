# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:212225230207
# Developed By:PON SARAVANA PANDIAN B
# 1-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)
# 2-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")
# Infinity Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)
```
## Output:
### 1-Norm of a Matrix

<img width="712" height="582" alt="Screenshot 2026-03-27 170947" src="https://github.com/user-attachments/assets/b943d44b-1b5e-48a9-a44a-3e75a4c9d7ec" />

### 2-Norm of a Matrix

<img width="721" height="676" alt="image" src="https://github.com/user-attachments/assets/d5523d1c-96dd-4ea4-b9ea-419a9b2d6d90" />


### Infinity Norm of a Matrix

<img width="720" height="589" alt="image" src="https://github.com/user-attachments/assets/4a7a9ee4-a1a3-48c9-a62e-46a340639859" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
