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
# Register No:23013924
# Developed By:GOKUL PRAKASH M
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: GOKUL PRAKASH M
RegisterNumber: 23013924
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
nom="{:.2f}".format(ans)
print(nom)


# Infinity Norm of a Matrix

#Program to find 2-norm of a matrix
#Devloped by:Gokul Prakash M
#Register no:23013924

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/gokulprakash23013924/Norm-of-a-matrix/assets/150231472/1f5b7f93-990b-4f4e-be44-a3972e9b9f15)


### 2-Norm of a Matrix
![image](https://github.com/gokulprakash23013924/Norm-of-a-matrix/assets/150231472/a4f3d42a-08b5-4183-8ac3-91279c7d826c)


### Infinity Norm of a Matrix
![image](https://github.com/gokulprakash23013924/Norm-of-a-matrix/assets/150231472/24bcd7b0-99b0-4911-a07b-c70fd4774357)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
