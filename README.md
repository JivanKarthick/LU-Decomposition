# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1. Import the scipy from the library,for lu decomposition.

2. Get the eval input from the user.

3. Assign the value for a,b.

4. printf the program

## Program:
```
(i) To find the L and U matrix

/*
Program to find the L and U matrix.
Developed by: Jivan Karthec.B.S
RegisterNumber: 22004763
*/
```
```
import numpy as np
from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)

```
```
(ii) To find the LU Decomposition of a matrix

/*
Program to find the LU Decomposition of a matrix.
Developed by:Jivan Karthec.B.S 
RegisterNumber: 22004763
*/
```
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![zzzz](https://user-images.githubusercontent.com/121165867/214799441-859b63fe-0c2e-4677-aa6c-38c208946bdc.png)
![cccccc](https://user-images.githubusercontent.com/121165867/214799496-838d6d0a-7850-4987-900a-20bd04c722b3.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

