# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber: 
*/
import numpy as np
from scipy.linalg import lu 
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
import numpy as np
from scipy.linalg import lu_factor , lu_solve
A=eval(input())
b=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

*/
```

## Output:
![Screenshot 2022-02-06 214657](https://user-images.githubusercontent.com/94828138/152690304-328f2d54-0554-46f4-b58f-c0b9d6b6adff.png)

![big onme ](https://user-images.githubusercontent.com/94828138/152690327-b9a38301-2ae0-4dbd-81e1-57129fb875b1.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

