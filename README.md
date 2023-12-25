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
# Register No:23000100
# Developed By:RUCHITRA THIYAGARAJ
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))

# 2-Norm of a Matrix
'''Developed by: Ruchitra Thiyagaraj
Register Number:23000100
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/RuchitraThiyagaraj/Norm-of-a-matrix/assets/154776996/45df09a5-3e77-438e-b2de-dd5cdcfca91f)

<br>
<br>
<br>

### 2-Norm of a Matrix
![image](https://github.com/RuchitraThiyagaraj/Norm-of-a-matrix/assets/154776996/ae826002-5986-467e-85dd-557664fccf90)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![image](https://github.com/RuchitraThiyagaraj/Norm-of-a-matrix/assets/154776996/94a29948-d6f8-4f37-9400-c2eff29efbab)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
