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
# Register No:23013501
# Developed By:sivakumar R
# 1-Norm of a Matrix

import numpy as np

arr=([[-1, 3],[3, -4],[1, 7]])

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,1)

norm_of_matrix="{:.2f}".format(ans)

print(norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,2)

norm="{:.2f}".format(ans)

print(norm)




# Infinity Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))

sol=np.linalg.norm(mat,np.inf)

norm="{:.2f}" .format(sol)

print(norm)




```
## Output:
### 1-Norm of a Matrix
<img width="535" alt="Screenshot 2024-04-06 205636" src="https://github.com/SIVAmech123/Norm-of-a-matrix/assets/151629067/1ac2094f-a4b2-4d37-90b6-2dda7a4ae715">

<img width="463" alt="Screenshot 2024-04-06 205646" src="https://github.com/SIVAmech123/Norm-of-a-matrix/assets/151629067/71fafc92-c04d-4c7f-a5a7-f8fb0f5f8c06">

### 2-Norm of a Matrix
<img width="519" alt="Screenshot 2024-04-06 205659" src="https://github.com/SIVAmech123/Norm-of-a-matrix/assets/151629067/5202165e-9695-43c7-83f5-74f64ca81e93">

<img width="346" alt="Screenshot 2024-04-06 205706" src="https://github.com/SIVAmech123/Norm-of-a-matrix/assets/151629067/0e15f360-4bf8-42a0-9835-859339cff430">


### Infinity Norm of a Matrix
<img width="504" alt="Screenshot 2024-04-06 205714" src="https://github.com/SIVAmech123/Norm-of-a-matrix/assets/151629067/753b609e-343c-4cf7-966b-12d543feb778">

<img width="458" alt="Screenshot 2024-04-06 205723" src="https://github.com/SIVAmech123/Norm-of-a-matrix/assets/151629067/8bc81ee8-01bf-4aae-ab24-a2432a2fa885">


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
