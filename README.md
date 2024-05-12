# Read-from-CSV
## NAME: DEVA DHARSHINI I

## REGISTER NO: 212223240026
## AIM:
To write a python program for reading the csv file content

## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.
### Step 2:
Print the number of contents to be displayed using df.head().
### Step 3:
The number of rows returned is defined in Pandas option settings.
### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.
## PROGRAM:
```
To write a python program for reading content from a CSV file.
Developed by:DEVA DHARSHINI I
Register Number: 212223240026
import pandas as pd
df = pd.read_csv('salary.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2024-05-12 142526](https://github.com/deesk13/Read-from-CSV/assets/150927063/4805cc37-22d1-4eaa-814d-4d624da7a416)
## RESULT:
Thus the program is written to read the csv file.
