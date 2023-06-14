## Read-from-CSV
## AIM:

To write a python program to read contents from a CSV file.

## ALGORITHM:
### Step 1:
import panda module as pd

### Step 2:
Read the csv file

### Step 3:
print the first 10rows

### Step 4:
print the next 5rows

### Step 5:
print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
```python
#Program to read contents from a CSV file.
#Developed by: Kabilan V
#Reg No: 212222100018

import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("columns",df.axes[1])
print("no of rows",len(df.axes[0]))
print("no. of columns",len(df.axes[1]))
```

## OUTPUT:
![Screenshot from 2023-06-12 00-24-51](https://github.com/Alfredsec/Read-from-CSV/assets/120621608/ecaebe45-cb45-4ecf-b334-4bb3e23ccb4b)

## RESULT:
The program is executed successfully
