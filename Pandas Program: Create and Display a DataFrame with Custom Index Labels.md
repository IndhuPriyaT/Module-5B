# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```
import pandas as pd
import numpy as np
exam_data = {'name','score','attempts','qualify'}
label = [1,2,3,4]
df = pd.DataFrame(exam_data,label)
print(df)
```

## Output

<img width="253" height="224" alt="image" src="https://github.com/user-attachments/assets/2e9d6948-08de-4a01-9c89-537076f2a8f0" />



## Result
Thus , a to create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows is successfully executed.
