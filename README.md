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
# Register No: 212222240113
# Developed By: VASANTH P

# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)


# 2-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)



# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)
```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/Vasanthpushpa/Norm-of-a-matrix/assets/119291100/cba9c2c5-ceea-4488-b0c7-a6c82e779afe)

### 2-Norm of a Matrix

![image](https://github.com/Vasanthpushpa/Norm-of-a-matrix/assets/119291100/2613e45e-422c-47fe-a308-10d064ad1c5f)

### Infinity Norm of a Matrix

![image](https://github.com/Vasanthpushpa/Norm-of-a-matrix/assets/119291100/e4af6143-cbfe-42cb-b185-1c4de8dd6e87)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
