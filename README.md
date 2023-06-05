## Read-from-CSV
## AIM:
To write a python program for reading the csv file content.

## ALGORITHM:
## Step 1:
Load the CSV into a DataFrame.

## Step 2:
Print the number of contents to be displayed using df.head().

## Step 3:
The number of rows returned is defined in Pandas option settings.

## Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.

## Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
Developed by:Narendran

REGISTER NUMBER: 212222240069
```
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/naren2704/Read-from-CSV/assets/118706984/3420609d-0482-4865-bd08-3cb44dda9343)
## RESULT:
Thus the program is written to read the csv file.
