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
#Program to find of given matrix
# Register No:23013599
# Developed By:Suriya prakash.S

# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/arulsuriyalokeshy/Norm-of-a-matrix/assets/149130151/3d5a875c-d91a-49bb-84d9-3b79933b12e1)

### 2-Norm of a Matrix
![image](https://github.com/arulsuriyalokeshy/Norm-of-a-matrix/assets/149130151/923dc9d3-a103-42da-aced-7f1834a9cad9)

### Infinity Norm of a Matrix
![image](https://github.com/arulsuriyalokeshy/Norm-of-a-matrix/assets/149130151/5d2edf94-6974-43a5-a08d-e720954f159b)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
