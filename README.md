# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
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
`````
#To write a python program for reading content from a CSV file.
#Developed by: KRISHNA KUMAR R
#Register Number: 212223230107

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```````

### OUTPUT:

![329156316-f0a48c59-392e-4aa2-be43-326dca874b38](https://github.com/Krishna23013541/Copy-File/assets/149557764/53450517-f9e1-4146-9824-5773d208ca6f)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
