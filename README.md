# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu
2. Get input from user and print Land U matrix by 'print'
3. Define a package  as "from scipy.linalg import lu_factor,lu_solve"and create the
  variable as 'x' include the package in the variable.

4.print the variable 'x' 
   

## Program:

(i) To find the L and U matrix

```python
#Program to find the L and U matrix.
#Developed by: NANDHINI.S
#RegisterNumber: 24013591
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
 ```

(ii) To find the LU Decomposition of a matrix

```python
#Program to find the LU Decomposition of a matrix.
#Developed by: NANDHINI.S
#RegisterNumber: 24013591
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```
## Output:
![alt text](<Screenshot 2024-12-08 182107-1.png>)
![alt text](<Screenshot 2024-12-08 182123-3.png>)

## Result:

Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.