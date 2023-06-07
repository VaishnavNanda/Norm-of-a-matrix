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
### 1-Norm of a Matrix
```
'''
Program to find 1-norm of a matrix.
Developed by: A.Thiyagarajan
RegisterNumber: 212222240110
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
### 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: A.Thiyagarajan
RegisterNumber: 212222240110
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
### Infinity Norm of a Matrix
```

'''
Program to find infinity of a matrix.
Developed by: A.Thiyagarajan
RegisterNumber: 212222240110
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix


![n1](https://github.com/A-Thiyagarajan/Norm-of-a-matrix/assets/118707693/951b8d1d-cc86-4044-94b7-b7add94c2877)


### 2-Norm of a Matrix



![n2](https://github.com/A-Thiyagarajan/Norm-of-a-matrix/assets/118707693/e0abda59-fc89-4a44-b828-34e373ae7f9d)


### Infinity Norm of a Matrix

![n3](https://github.com/A-Thiyagarajan/Norm-of-a-matrix/assets/118707693/e3ace661-05a7-40d0-8421-44ee13b35209)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
