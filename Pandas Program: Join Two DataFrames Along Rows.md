# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program

```
import pandas as pd
student_data1  = pd.DataFrame({
    'A': [1, 2],
    'B': [3, 4]
})

student_data2 = pd.DataFrame({
    'A': [5, 6],
    'B': [7, 8]
})
new = pd.concat([student_data1,student_data2],axis = 0)
print(pd.DataFrame(new))
```

## Output

<img width="156" height="224" alt="image" src="https://github.com/user-attachments/assets/3429feb0-38e5-4914-852f-b7339cf61834" />




## Result

Thus , a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame is executed successfully.
