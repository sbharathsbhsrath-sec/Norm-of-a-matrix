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
# Register No:212225230031
# Developed By:bharaths
# 1-Norm of a Matrix'
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
n="{:.2f}".format(ans)
print(n)




# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,2)
n="{:.2f}".format(a)
print(n)



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,np.inf)
n="{:.2f}".format(a)
print(n)




```
## Output:
### 1-Norm of a Matrix
<br>
<img width="861" height="199" alt="image" src="https://github.com/user-attachments/assets/47d10283-1d02-4def-8116-ccf4ea26301e" />

<br>

### 2-Norm of a Matrix
<br>
<img width="1274" height="279" alt="image" src="https://github.com/user-attachments/assets/8cba8e74-b0e3-4ae6-affb-928e524bcff8" />

<br>

### Infinity Norm of a Matrix
<br>
<img width="1261" height="244" alt="image" src="https://github.com/user-attachments/assets/ce48c32d-f3e4-40e7-b242-c997cabd5490" />

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
