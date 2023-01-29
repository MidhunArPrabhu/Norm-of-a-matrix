# EXPERIMENT-07
# NORM OF A MATRIX
## AIM :

To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## EQUIPMENTS REQUIRED :

- Hardware – PCs  
- Anaconda – Python 3.7 Installation / Moodle-Code Runner

## ALGORITHIM :

1. Get the input matrix using np.array()   

2. Find the 2-norm of the matrix using np.linalg.norm()

3. Print the norm of the matrix in two decimal places.

## PROGRAM :

```Python
# Register No: 22008311
# Developed By: MIDHUN AZHAHU RAJA P
# 1-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat, 1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat, 2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat, np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
## OUTPUT :

### 1-Norm of a Matrix
![image](https://user-images.githubusercontent.com/118054670/214359880-24729b3b-4d70-4157-8e6d-bf0f22473f2f.png)


### 2-Norm of a Matrix

![image](https://user-images.githubusercontent.com/118054670/214360047-816de019-85d2-49c5-a662-88637b0a7f1f.png)


### Infinity Norm of a Matrix
![image](https://user-images.githubusercontent.com/118054670/214360110-33fab379-c0fb-427d-a400-3aea21557abd.png)

## RESULT :

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
