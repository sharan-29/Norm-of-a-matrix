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
# Register No:24003909
# Developed By:Sharan Kumar G

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
matrix=np.array(mat)
a=(np.max(np.sum(np.abs(mat),axis=1)))
print(f"{a:.2f}")

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/9b662fdc-3a34-4938-8f2d-ce8d0cdd48b6)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/8145c69d-b207-4649-9297-9b9932e66e73)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/20c8a351-6fcf-4e17-a5e3-f9a36d3db6a3)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
