# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

### Program-1
1.Get the input matrix using np.array()   

2.Find the 1-norm of the matrix using np.linalg.norm()

3.Print the norm of the matrix in two decimal places.

### Program-2

1.Get the input matrix using np.array()

2.Find the 2-norm of the matrix using np.linalg.norm()

3.Print the norm of the matrix in two decimal places.

### Program-3

1.Get the input matrix using np.array()

2.Find the infinity-norm of the matrix using np.linalg.norm()

3.Print the norm of the matrix in two decimal places.
## Program:
```
# Register No:24006289
# Developed By:S.Dhayalaprabu

# 1-Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))
ans= np.linalg.norm(mat,1)
Norm_of_matrix=f"{ans:.2f}"
print(Norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np

mat=np.array(eval(input()))
ans= np.linalg.norm(mat,2)
L2_Norm_of_matrix=f"{ans:.2f}"
print(L2_Norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np

mat=np.array(eval(input()))
ans= np.linalg.norm(mat,np.inf)
Norm_of_matrix=f"{ans:.2f}"
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![output](exp-7.1.png)

### 2-Norm of a Matrix
![output](exp-7.2.png)

### Infinity Norm of a Matrix
![output](exp-7.3.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
