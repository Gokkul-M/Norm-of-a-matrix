# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
### 1.Hardware – PCs
### 2.Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step.1:
Get the input matrix using np.array()   
### Step.2:
Find the 1-norm,2-norm and infinite norm of the matrix using np.linalg.norm().
### Step.3:
Print the norm of the matrix in two decimal places.
### Step.4:
End the program.
## Program:
```
'''
Program to find the 1-Norm of a matrix
Developed by:Gokkul M
Register Number:212223240039
'''
```
```
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
```
# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
```
# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Gokkul-M/Norm-of-a-matrix/assets/144870543/b8c4aa54-21e0-47e7-b9d8-75ce8d0abc2b)
### 2-Norm of a Matrix
![image](https://github.com/Gokkul-M/Norm-of-a-matrix/assets/144870543/866c83ad-fb38-458c-8392-b44b58d7e351)
### Infinity Norm of a Matrix
![image](https://github.com/Gokkul-M/Norm-of-a-matrix/assets/144870543/0683e26e-b63f-4d40-98e4-cf22084f6177)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
