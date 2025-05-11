# Pandas Program:  To  replace all negative numbers in the dataframe with 0.

## 🎯 Aim

To create a DataFrame from user input and display it after replacing all negative values with 0, demonstrating basic DataFrame creation and element-wise conditional value replacement using pandas.



## 🧠 Algorithm

1. Take a 2D list of numbers as input.
2. Convert the list into a pandas DataFrame.
3. Display the original DataFrame.
4. Replace all negative values in the DataFrame with 0.
5. Display the modified DataFrame. 



## 💻 Program
```
import pandas as pd
a=pd.DataFrame(eval(input()))
print("Data Frame")
print(a)
print("Display DataFrame after replacing every negative value with 0")
a[a<0]=0
print(a)
```

## Output
![image](https://github.com/user-attachments/assets/a2bbcbf2-8ba9-49ef-ad15-2cb2c9c02050)


## Result
Thus the program executed successfully.
