
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

# Register No: 212224100042
# Developed By:PRAISY NISHITHA J
## 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
n="{:2f}".format(ans)
print(n)
```


## 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```


## Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
<img width="1446" height="970" alt="image" src="https://github.com/user-attachments/assets/ec368ff8-de95-43cb-afa0-c6831d3f37c3" />
<

### 2-Norm of a Matrix
<img width="1456" height="720" alt="image" src="https://github.com/user-attachments/assets/0d806c08-ce42-4edd-9fab-1ebadff97c9d" />


### Infinity Norm of a Matrix
<img width="1292" height="832" alt="image" src="https://github.com/user-attachments/assets/39734704-3524-4c16-9887-e4eb3f3df03a" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
