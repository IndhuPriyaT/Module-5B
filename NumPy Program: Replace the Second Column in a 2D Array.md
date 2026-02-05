# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program

```
import numpy as np
l1 = eval(input())
arr = np.array(l1)
new = arr.reshape(2, 3)
co = np.array(eval(input()))
co = co.reshape(2, 1)
delete = np.delete(new, 1, axis=1)
insert = np.insert(delete, 1, co, axis=1)
print(insert)
```

## Output

<img width="308" height="197" alt="image" src="https://github.com/user-attachments/assets/2ae89975-17ac-4e89-8415-07f6a17d3466" />


## Result
Thus , a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position is successfully executed.
