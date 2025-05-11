# # NumPy Program:  Find the sum of last column in a given numpy array

## 🎯 Aim
To write a Python program using **NumPy** that find the sum of last column in a given numpy array

## 🧠 Algorithm
1. Take a list of 12 numbers as input.
2. Convert the list into a NumPy array.
3. Reshape the array into a 4x3 matrix.
4. Calculate the sum of the third column.
5. Display the reshaped matrix and the column sum.


## 🧾 Program
```

import numpy as np
a=eval(input())
z=np.array(a)
n=z.reshape(4,3)
print(n)
s=np.sum(n[:,2])
print(s)
```

## Output
![image](https://github.com/user-attachments/assets/f771d0a7-65e1-445d-a818-692b26674445)


## Result
Thus the program executed successfully.
