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
#program to find the 1-Norm of a matrix 
#Developed by: D Vergin Jenifer
#Register no.: 23004210
# 1-Norm of a Matrix:
import numpy as np
def one_norm(matrix):
    result=np.linalg.norm(matrix,ord=1)
    return "{:.2f}".format(result)
matrix=eval(input())
matrix=np.array(matrix)
result=one_norm(matrix)
print(result)

# 2-Norm of a Matrix:
import numpy as np
def two_norm(matrix):
    result=np.linalg.norm(matrix,ord=2)
    return "{:.2f}".format(result)
matrix=eval(input())
matrix=np.array(matrix)
result=two_norm(matrix)
print(result)

# Infinity Norm of a Matrix:
import numpy as np
def two_norm(matrix):
    result=np.linalg.norm(matrix,ord=np.inf)
    return "{:.2f}".format(result)
matrix=eval(input())
matrix=np.array(matrix)
result=two_norm(matrix)
print(result)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/VerginJenifer/Norm-of-a-matrix/assets/136251012/eeb294fd-e170-4c46-b772-c0d13595c485)


### 2-Norm of a Matrix
![image](https://github.com/VerginJenifer/Norm-of-a-matrix/assets/136251012/8a534c4b-2937-4b1d-b62f-114fc1f99e97)

### Infinity Norm of a Matrix
![image](https://github.com/VerginJenifer/Norm-of-a-matrix/assets/136251012/2a941b02-bbf7-4665-b67d-3c3fe50fa119)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
