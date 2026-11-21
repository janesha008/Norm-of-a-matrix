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
# Register No: 212225240056
# Developed By: Janesha S
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix


<img width="1897" height="917" alt="image" src="https://github.com/user-attachments/assets/4c1cd4ee-2075-4ed5-8edb-0ed7efec4b3b" />

### 2-Norm of a Matrix


<img width="1902" height="737" alt="image" src="https://github.com/user-attachments/assets/6337c71a-c5f4-46c5-86f6-6e595926efdd" />

### Infinity Norm of a Matrix


<img width="1907" height="920" alt="image" src="https://github.com/user-attachments/assets/bb82186f-67ea-4e78-b7c8-1c16c8a04f74" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
