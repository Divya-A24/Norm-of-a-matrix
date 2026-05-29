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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)

# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm: .2f}")
# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)





```
## Output:
### 1-Norm of a Matrix
<img width="1131" height="809" alt="image" src="https://github.com/user-attachments/assets/4413c035-03a8-4878-a840-d5394cb7ae48" />
<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="748" height="835" alt="image" src="https://github.com/user-attachments/assets/3306017d-e8f0-4f2b-91fe-847ba917fe79" />
<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="770" height="822" alt="image" src="https://github.com/user-attachments/assets/4c5fb955-005f-4f8b-8aca-9a887ebd333e" />
<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
