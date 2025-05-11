# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np
array=np.array(eval(input()))
print(array)
sort=np.sort(array.flatten())
print()
print(sort)
```

## Output
![image](https://github.com/user-attachments/assets/a9e2d0f3-8c02-4041-b278-80b386696254)


## Result
Thus the program executed successfully.
