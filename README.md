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
# Register No:
# Developed By:
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,1)
print("{:.2f}".format(ans))



# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,2)
print("{:.2f}".format(ans))



# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,np.inf)
print("{:.2f}".format(ans))




```
## Output:
### 1-Norm of a Matrix
![Screenshot (153)](https://user-images.githubusercontent.com/121148715/213900663-b417b66c-f0f6-4403-960e-f6fa575fd230.png)

<br>
<br>
<br>

### 2-Norm of a Matrix
![Screenshot (154)](https://user-images.githubusercontent.com/121148715/213900666-453b45b6-68e2-41ea-8613-b3565a35bc7a.png)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![Screenshot (155)](https://user-images.githubusercontent.com/121148715/213900671-21e448ac-7c66-450d-a10c-c5eb22ca89b1.png)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
