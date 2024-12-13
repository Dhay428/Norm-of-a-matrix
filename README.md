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
![Screenshot 2024-12-13 121300](https://github.com/user-attachments/assets/94e24af3-8b0e-43d8-9771-b74b1be7a83e)

### 2-Norm of a Matrix
![Screenshot 2024-12-13 121320](https://github.com/user-attachments/assets/5e9bc60a-8063-45b2-a5af-842708281e68)

### Infinity Norm of a Matrix
![Screenshot 2024-12-13 121334](https://github.com/user-attachments/assets/e6f05cae-8d12-4210-803a-1e9cee779089)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
