# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Import the NumPy as np.
 2. Store the user input using np.array() and store it in a variable named mat.
 3. Find the 1-Norm of the matrix using np.linalg.norm(mat, 1) and also the 2-Norm of the matrix
 using np.linalg.norm(mat, 2).
 4. Find the Infinity Norm of the matrix using np.linalg.norm(mat, np.inf).
 5. Print the 1-Norm, 2-Norm, and Infinity Norm values of the matrix as the final output

	
## Program:
Name : Rahul RP
Reg num : 212224240125
```Python
#1
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix

'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

#3 Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix

<img width="1719" height="480" alt="image" src="https://github.com/user-attachments/assets/16fcf54a-e4f2-429b-8db0-5f28f8d6eae8" />



### 2-Norm of a Matrix

<img width="1716" height="534" alt="image" src="https://github.com/user-attachments/assets/76ffb67b-5cbb-44b4-89d0-15fac140ffb8" />



### Infinity Norm of a Matrix


<img width="1721" height="472" alt="image" src="https://github.com/user-attachments/assets/54a8f877-c83c-480e-88a5-eefeaeb79016" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
