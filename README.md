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
# Register No:24900203
# Developed By:Akbar.I
# 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```



# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```



# Infinity Norm of a Matrix

```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```



```
## Output:
### 1-Norm of a Matrix
<br>![Screenshot 2024-12-13 090349](https://github.com/user-attachments/assets/cec84d30-56f2-4411-92c2-4d75d184df64)

<br>
<br>

### 2-Norm of a Matrix
<br>![Screenshot 2024-12-13 090404](https://github.com/user-attachments/assets/f381d0f4-bd97-45d1-bd5d-addd06fafb0e)


<br>
<br>

### Infinity Norm of a Matrix
<br>![Screenshot 2024-12-13 090416](https://github.com/user-attachments/assets/d5bbc7dc-b32e-491e-933c-f4f73d08197d)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
