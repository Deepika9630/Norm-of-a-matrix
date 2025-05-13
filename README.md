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
# Developed by: Deepika.R
# RegisterNumber: 212224230054
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix

![Screenshot 2025-05-13 192732](https://github.com/user-attachments/assets/a11d15cc-52f5-4d47-b49d-ea72c04bcbde)

### 2-Norm of a Matrix

![Screenshot 2025-05-13 192739](https://github.com/user-attachments/assets/71f977ba-c922-42f5-b457-45a06096445b)

### Infinity Norm of a Matrix

![Screenshot 2025-05-13 192745](https://github.com/user-attachments/assets/c437c961-d83d-44db-a6f5-e89fe2bf15fc)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
