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
# Register No:RAGUNATH R
# Developed By:2122222240081
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))


# 2-Norm of a Matrix
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
![image](https://github.com/Ragu-123/Norm-of-a-matrix/assets/113915622/660c313b-0c49-4c8f-85b3-bd02368554df)

### 2-Norm of a Matrix
![image](https://github.com/Ragu-123/Norm-of-a-matrix/assets/113915622/1c8050e0-2358-4ea2-a49f-41c0f27a048f)


### Infinity Norm of a Matrix
![image](https://github.com/Ragu-123/Norm-of-a-matrix/assets/113915622/7ca520f7-1567-4d20-8821-ac8f2349fac8)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
