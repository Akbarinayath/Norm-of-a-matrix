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
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norms_of_matrix="{:.2f}".format(ans)
print(norms_of_matrix)



# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norms="{:.2f}".format(ans)
print(norms)




```
## Output:
### 1-Norm of a Matrix
![Screenshot (29)](https://github.com/user-attachments/assets/dd4caa89-c6e4-4a47-9260-615464b0f8cc)


### 2-Norm of a Matrix

![Screenshot (30)](https://github.com/user-attachments/assets/0721cb01-bf86-4c28-a4ce-80479d5baa9a)

### Infinity Norm of a Matrix

![Screenshot (31)](https://github.com/user-attachments/assets/651c5377-30bd-4c0f-8388-2c8ba9d16246)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
