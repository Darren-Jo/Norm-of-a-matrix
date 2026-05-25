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
# Register No: 212225230039
# Developed By: K DARREN JOSEPH
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))






# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))




```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
<img width="561" height="182" alt="image" src="https://github.com/user-attachments/assets/b22dc0b3-f738-497a-a23a-adfa0f1b4479" />


### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="522" height="230" alt="image" src="https://github.com/user-attachments/assets/35f87986-4a62-47f2-81cc-1323d897a247" />


### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="552" height="190" alt="image" src="https://github.com/user-attachments/assets/3779e248-d8de-43dd-8680-70bb3ca3d891" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
