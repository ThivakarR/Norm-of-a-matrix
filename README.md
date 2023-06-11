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
mat = np.array(eval(input()))
a=np.linalg.norm(mat,1)
norm="{:.2f}".format(a)
print(norm)





# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
a=np.linalg.norm(mat,2)
norm="{:.2f}".format(a)
print(norm)




# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
a=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(a)
print(norm)






```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-06-11 164416](https://github.com/ThivakarR/Norm-of-a-matrix/assets/118707074/26c9d308-a113-4452-99b5-90ab3ce34a1e)


### 2-Norm of a Matrix

![Screenshot 2023-06-11 164425](https://github.com/ThivakarR/Norm-of-a-matrix/assets/118707074/4c353fb0-71de-442d-8949-971c842b3b2e)

### Infinity Norm of a Matrix
<br>
<br>
<br>
![Screenshot 2023-06-11 164439](https://github.com/ThivakarR/Norm-of-a-matrix/assets/118707074/80bfbec1-5e35-4958-b229-b9e008d2cefe)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
