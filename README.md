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
# Register No: 212223100058
# Developed By: Thaksha Rishi
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
nm="{:.2f}".format(ans)
print(nm)



# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
nm="{:.2f}".format(ans)
print(nm)




# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
nm="{:.2f}".format(ans)
print(nm)





```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>

![Alt text](<Screenshot 2023-12-31 154823.png>)
### 2-Norm of a Matrix
<br>
<br>
<br>

![Alt text](<Screenshot 2023-12-31 154842.png>)
### Infinity Norm of a Matrix
<br>
<br>
<br>

![Alt text](<Screenshot 2023-12-31 154852.png>)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
