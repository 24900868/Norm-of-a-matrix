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
# Register No:212224230148
# Developed By: M.Mahalakshmi
# 1-Norm of a Matrix
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,1)
n="{:.2f}".format(a)
print(n)



# 2-Norm of a Matrix
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,2)
n="{:.2f}".format(a)
print(n)



# Infinity Norm of a Matrix
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,np.inf)
n="{:.2f}".format(a)
print(n)
```
## Output:
### 1-Norm of a Matrix

![Screenshot 2025-04-21 132837](https://github.com/user-attachments/assets/267b7e20-7bb5-4502-a15a-112723ff3207)


### 2-Norm of a Matrix

![Screenshot 2025-04-21 132903](https://github.com/user-attachments/assets/956e9ff2-fcbc-4ee9-80d8-99e5f7fa25a9)


### Infinity Norm of a Matrix

![Screenshot 2025-04-21 132912](https://github.com/user-attachments/assets/23278e88-598b-4984-8959-181bdc33ff2d)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
