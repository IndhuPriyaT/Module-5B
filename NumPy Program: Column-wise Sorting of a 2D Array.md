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

data = np.array([[30, 10, 20], 
                 [5,  45, 15], 
                 [50, 25,  2]])

sorted_array = np.sort(data, axis=0)

print("Original Array:")
print(data)
print("Column-wise Sorted Array:")
print(sorted_array)
```

## Output

<img width="431" height="333" alt="image" src="https://github.com/user-attachments/assets/c4901fb6-c608-4256-b83f-405045611593" />



## Result
Thus , a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order is successfully executed.
