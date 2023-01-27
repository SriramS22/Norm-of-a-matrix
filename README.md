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
# Register No:22009336
# Developed By: Sriram.S
# 1-Norm of a Matrix
import numpy as np 
a=np.array(eval(input()))
n = np.linalg.norm(a,1)
print("{:.2f}".format(n))




# 2-Norm of a Matrix
import numpy as np 
a=np.array(eval(input()))
n = np.linalg.norm(a,2)
print("{:.2f}".format(n))




# Infinity Norm of a Matrix
import numpy as np 
a=np.array(eval(input()))
n = np.linalg.norm(a,2)
print("{:.2f}".format(n))





```
## Output:
### 1-Norm of a Matrix
![norm 1](https://user-images.githubusercontent.com/119094390/215099161-be99bd7d-f94d-49a6-8b7f-2b270025fdb9.png)


### 2-Norm of a Matrix
![norm 2](https://user-images.githubusercontent.com/119094390/215099253-f7e82cfd-416a-4fd5-ab36-a8ee548f1a76.png)


### Infinity Norm of a Matrix
![norm 3](https://user-images.githubusercontent.com/119094390/215099308-d8ef126d-cc2a-4e36-9043-972f7958ed9b.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
