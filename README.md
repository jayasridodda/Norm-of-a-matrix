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
# Register No: 212222240028
# Developed By: JAYASRI DODDA
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)

# 2-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
n=np.linalg.norm(arr,2)
print("{:.2f}".format(n))

# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)

```
## Output:
### 1-Norm of a Matrix
![Screenshot (50)](https://github.com/jayasridodda/Norm-of-a-matrix/assets/123259278/22e5d943-57f5-46be-849c-131251e43621)

### 2-Norm of a Matrix
![Screenshot (51)](https://github.com/jayasridodda/Norm-of-a-matrix/assets/123259278/9b0dfddc-1be9-486d-a499-830e9deb0743)

### Infinity Norm of a Matrix
![Screenshot (52)](https://github.com/jayasridodda/Norm-of-a-matrix/assets/123259278/f9d145e4-9aad-4e87-8f13-43a3d4c68a4f)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
