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
# Register No:212224040022
# Developed By: ANAND K 
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
![image](https://github.com/user-attachments/assets/6fd37633-9b4f-4eac-8ac4-15eadf999d19)

### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/a08194f5-a8e2-46cd-8d5b-aa9a18c3807c)



### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/a8b1cf21-73e1-4348-9c5c-f12a87bbe377)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
