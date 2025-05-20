# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
import numpy as np
### Step 2:
from scipy package import lu
### Step 3:
get input from the user
### Step 4:
print result
## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv),B)
print(x)

```

## Output:
![Screenshot 2025-05-20 135538](https://github.com/user-attachments/assets/ea10ca0e-c896-40a6-902d-c9e514853b81)
![Screenshot 2025-05-20 135556](https://github.com/user-attachments/assets/c817b2fc-6351-4e46-8fa5-1647a318d4e5)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

