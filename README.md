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

#Program to find 1-norm of a matrix.
#Developed by: T.Thrishendra
#RegisterNumber:212223230227

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))
```
```
#Program to find 2-norm of a matrix.
#Developed by: T.Thrishendra
#RegisterNumber:212223230227

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))
```
```
#Program to find infinity-norm of a matrix.
#Developed by: T.Thrishendra
#RegisterNumber:212223230227

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-24 204359](https://github.com/Thrishendra/Norm-of-a-matrix/assets/145742464/09267739-5855-4a81-aca5-a5285d6ab09c)


### 2-Norm of a Matrix
![Screenshot 2023-12-24 204418](https://github.com/Thrishendra/Norm-of-a-matrix/assets/145742464/6c00d2d5-9013-4030-8ff1-f1e7f98f5735)

### Infinity Norm of a Matrix
![Screenshot 2023-12-24 204437](https://github.com/Thrishendra/Norm-of-a-matrix/assets/145742464/2d4b3835-3ad6-421f-8005-3ac8dada7bd9)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
