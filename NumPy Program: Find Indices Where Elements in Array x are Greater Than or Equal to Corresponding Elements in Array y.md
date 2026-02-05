# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program

```
import numpy as np
x = np.array([[10,20,30],
              [2,4,5],
              [34,45,67]])
y = np.array([[1,2,3],
              [12,13,14],
              [9,7,6]])
print(np.where(x>y,True,False))
print()
print(np.where(x==y,True,False))
```

## Output

<img width="427" height="305" alt="image" src="https://github.com/user-attachments/assets/13a7e4a6-e79d-4a3a-ad8d-fd483cb15a2d" />



## Result

Thus , a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`is successfully executed.

