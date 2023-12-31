# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.Hardware – PCs
2.Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
### Program:
~~~
# 1-Norm of a Matrix
'''
#Program to find 1-norm of a matrix.
#Developed by: Dhanusya K
#RegisterNumber: 23006651 
'''
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
~~~

# 2-Norm of a Matrix
'''
~~~
Program to find 2-norm of a matrix.
Developed by: Dhanusya K
RegisterNumber: 23006651
'''
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
~~~



# Infinity Norm of a Matrix
'''
~~~
Program to find Infinity norm of a matrix.
Developed by: Dhanusya K
RegisteredNumber: 23006651
'''
import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


~~~


### Output:

### 1-Norm of a Matrix
![Screenshot 2023-12-31 161059](https://github.com/Dhanu654/Norm-of-a-matrix/assets/148514965/d4a09e9a-a518-4de8-a4eb-bf5f2f05ca79)


### 2-Norm of a Matrix
![Screenshot 2023-12-31 161144](https://github.com/Dhanu654/Norm-of-a-matrix/assets/148514965/c4bf4533-9093-4ab9-a53e-76693e4b1bcc)


### Infinity Norm of a Matrix
![Screenshot 2023-12-31 161225](https://github.com/Dhanu654/Norm-of-a-matrix/assets/148514965/3366a210-c8fc-4daa-b7b6-4fac1d7db992)


### Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
