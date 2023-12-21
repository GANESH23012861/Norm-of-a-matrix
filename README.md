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
# 1-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: selva kumar R.
RegisterNumber: 23012861
'''
import numpy as np
value = eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print('{:.2f}'.format(norm))




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: selva kumar R.
RegisterNumber:  23012861
'''
import numpy as np
value = eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print('{:.2f}'.format(norm))




# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: selva kumar R.
RegisterNumber:  23012861
'''
import numpy as np
value = eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print('{:.2f}'.format(norm))





```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-21 214951](https://github.com/GANESH23012861/Norm-of-a-matrix/assets/147139861/f60c0d4d-f9e6-4780-92b8-098e1b8c6420)

### 2-Norm of a Matrix
![Screenshot 2023-12-21 215007](https://github.com/GANESH23012861/Norm-of-a-matrix/assets/147139861/8d9e38f3-0b67-41cd-a6ae-44f8a920caad)

### Infinity Norm of a Matrix
![Screenshot 2023-12-21 215019](https://github.com/GANESH23012861/Norm-of-a-matrix/assets/147139861/a0321eda-6b6e-4729-a32a-a01cf483b7f2)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
