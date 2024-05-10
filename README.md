## Norm of a Matrix

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

# Register No : PRAKASH C
# Developed By : 212223240122

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

![Screenshot 2024-05-10 205205](https://github.com/Prakash-Chandran/Norm-of-a-matrix/assets/147120899/0ffb99e2-69d8-44ac-9588-5fef0b66ee91)


### 2-Norm of a Matrix

![Screenshot 2024-05-10 205240](https://github.com/Prakash-Chandran/Norm-of-a-matrix/assets/147120899/32560584-3c92-4342-8ba2-c574d2a6acf6)


### Infinity Norm of a Matrix

![Screenshot 2024-05-10 205303](https://github.com/Prakash-Chandran/Norm-of-a-matrix/assets/147120899/6e6b215d-50d6-4f09-9ffc-471e2f69be46)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
