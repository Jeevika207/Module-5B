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

student_data1 = {
    'Name': ['Alice', 'Bob'],
    'Age': [20, 21],
    'Grade': ['A', 'B']
}

student_data2 = {
    'Name': ['Charlie', 'David'],
    'Age': [19, 22],
    'Grade': ['C', 'A']
}

df1 = pd.DataFrame(student_data1)
df2 = pd.DataFrame(student_data2)

combined_df = pd.concat([df1, df2], axis=0)
print(combined_df)
```

## Output
<img width="357" height="257" alt="image" src="https://github.com/user-attachments/assets/476616c6-4e1a-4856-aa98-80b26c15080e" />


## Result

Hence, the code is executed successfully, and the two DataFrames are joined row-wise to form a new combined DataFrame.
